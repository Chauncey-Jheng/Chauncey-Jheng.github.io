---
title: "Noise-Robust Bearing Fault Diagnosis: Dual-Branch LLM Co-Evolution"
excerpt: "An LLM-driven adversarial co-evolution framework where a noise-generating branch and a model-architecture branch alternately drive each other to boost robustness under complex industrial noise."
collection: portfolio
---

**Collaboration: BJUT × Australian National University (ANU) · 2026.03 – 2026.05**

- 提出双分支 LLM 对抗协同演化框架：噪声分支基于工业噪声领域特定语言（DSL，9 类噪声原语），由 LLM 针对模型最薄弱单元（worst-cell）定向演化更具挑战性的噪声；模型分支通过进化搜索自动优化 FCN 分类器架构，两分支交替对抗、螺旋提升噪声鲁棒性。
- 设计完整对照体系（固定噪声增强 / 随机 DSL / LLM 演化 / 架构演化）与 worst-cell 平衡精度评估，覆盖宽带、复杂工业、跨数据集与真实采集四类噪声场景。
- 复现 BearLLM 基线（MBHM 98.89%）；复杂工业噪声场景（B-CPLX）worst-cell 平衡精度由 0.3376 提升至 **0.6909（+105%）**，显著突破固定手工噪声增强的性能上限。
