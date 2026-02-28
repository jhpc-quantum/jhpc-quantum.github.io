
---

# 🔗 _docs/hybrid-workflow.md（ハイブリッド統合ワークフロー）

```markdown
---
title: Hybrid Workflow
nav_order: 8
---

# Hybrid Workflow

HPC ↔ QPU を連携させるワークフロー。

## VQE Workflow
1. 分子ハミルトニアンを HPC で生成  
2. QPU でエネルギー評価  
3. HPC でパラメータ最適化  
4. 収束まで繰り返し

## QSCI Hybrid Workflow
1. Determinant 選択（HPC）  
2. 振幅評価（QPU）  
3. CI space 拡張  
4. 再帰的更新
