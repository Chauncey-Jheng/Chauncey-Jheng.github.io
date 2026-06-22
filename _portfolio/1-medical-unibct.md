---
title: "Medical Multimodal: Brain CT Report Generation & Unified Modeling (UniBCT-Tok)"
excerpt: "Fine-grained cross-modal alignment, pathology knowledge graphs, and an entropy-driven semantic-balanced visual tokenizer for unified brain-CT understanding & generation.<br/><img src='/images/paper_img/UniBCT_Tok_framework.png' style='max-width:480px;width:100%;'>"
collection: portfolio
---

**Collaboration: BJUT × Peking University Third Hospital · 2023.12 – present**

为脑 CT 等医学影像自动生成结构化诊断报告，并迈向统一多模态建模：

- 设计细粒度跨模态对齐机制，结合 SAM 图像分割对齐，获得多模态一致性表示。
- 构建医学病理知识图谱，经图神经网络与互注意力进行跨模态特征融合；提出基于知识图谱的自适应知识平衡提示，显著提升小样本场景下的报告生成准确性。
- 提出 **UniBCT-Tok** 熵驱动语义均衡视觉分词器与统一多模态建模框架：token 压缩率 >75%、推理加速 44.8%，报告生成与图像合成均达 SOTA。

**Outcomes:** EMNLP 2024 · AAAI 2025 (Oral) · CVPR 2026 (Findings, UniBCT-Tok).
