---
title: "Detached Skip-Links and R-Probe: Decoupling Feature Aggregation from Gradient Propagation for MLLM OCR"
collection: publications
category: conferences
permalink: /publication/2026-07-13-detached-skip-links
excerpt: 'Decouples shallow-feature aggregation from gradient propagation via detached skip-links (forward concat, backward stop-gradient, zero extra parameters), and introduces R-Probe to diagnose fine-grained visual information retained in visual tokens; consistent gains across multiple ViT backbones and 22 multimodal benchmarks.'
date: 2026-07-13
venue: 'International Conference on Machine Learning (ICML)'
citation: 'Z. Yuan, R. Yao, <strong>C. Zheng</strong>, Y. Zhao, D. Dong, and M. Zhang. (2026). &quot;Detached Skip-Links and R-Probe: Decoupling Feature Aggregation from Gradient Propagation for MLLM OCR.&quot; <i>International Conference on Machine Learning (ICML)</i>.'
---

针对 MLLM 多层特征融合（Skip-Links）在联合训练中引入的梯度干扰问题，提出 **Detached Skip-Links**——前向正常拼接浅层特征、反向对跳跃通路施加 stop-gradient，在零额外参数下解耦特征聚合与梯度传播；并设计 **R-Probe** 重建探针，以像素级重建损失定量诊断视觉 token 的细粒度信息保留程度。在多个 ViT backbone、7M 训练样本与 22 个多模态基准上稳定提升，OCR 任务增益显著。
