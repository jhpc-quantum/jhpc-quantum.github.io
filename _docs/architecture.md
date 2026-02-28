---
title: Architecture
nav_order: 3
---

# System Architecture

以下の 3 層構造を中心としたアーキテクチャを採用しています。

1. **HPC Backend**  
   - Fugaku  
   - GPU クラスタ  
   - MPI, OpenMP, SYCL

2. **Quantum Backend**
   - Gate-based (VQE, QAOA)
   - Analog/Annealing
   - ローカル / クラウド量子計算機

3. **Hybrid-Orchestrator**
   - VQE 外部ループ
   - QSCI / Selected-CI 反復計算
   - HPC ↔ QPU データ統合