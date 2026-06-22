---
title: "MLLM OCR: Detached Skip-Links & R-Probe (ICML 2026)"
excerpt: "Decoupling feature aggregation from gradient propagation to remove gradient interference in MLLM multi-layer feature fusion — consistent gains across 22 multimodal benchmarks."
collection: portfolio
---

**Research internship @ Qianfan Large-Model Team, Baidu AI Cloud · 2025.05 – 2026.01**

- 提升 Qianfan-VL 自然场景图像 OCR：设计多模型协同、多级并行的数据合成流水线，构建千万量级细粒度 OCR 合成数据集，在多个公开 OCR benchmark 上达到 SOTA。
- 针对 MLLM 多层特征融合（Skip-Links）联合训练中的梯度干扰问题，提出 **Detached Skip-Links**（前向拼接、反向 stop-gradient，零额外参数解耦特征聚合与梯度传播）与 **R-Probe** 重建探针。
- 在 7M 训练样本、22 个多模态基准上稳定提升，OCR 任务增益显著。

**Outcome:** ICML 2026.
