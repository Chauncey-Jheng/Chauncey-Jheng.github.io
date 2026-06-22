---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Chengxin_Zheng_CV.pdf"><i class="fas fa-file-pdf"></i> Download PDF version</a></p>

Education
======
* M.S. in Computer Science and Technology, Beijing University of Technology (BJUT), 2023 – 2026 (expected)
  * Avg. score 93/100, rank top 1%; advised by Prof. Junzhong Ji and Prof. Xiaodan Zhang.
* B.Eng. in Computer Science and Technology, Hefei University of Technology (HFUT), 2019 – 2023
  * GPA 3.79/4.3, rank top 5%.

Research Interests
======
Multimodal LLMs · Unified multimodal understanding & generation · Vision-language representation learning · Visual tokenization · Medical multimodal · MLLM OCR.

Experience
======
* **Research Intern**, Qianfan Large-Model Team, Baidu AI Cloud — Beijing, May 2025 – Jan 2026
  * Enhanced Qianfan-VL natural-scene OCR via a multi-model, multi-stage data-synthesis pipeline (10M-scale fine-grained OCR data); reached SOTA on public OCR benchmarks.
  * Proposed **Detached Skip-Links** and **R-Probe** to resolve gradient interference in MLLM multi-layer feature fusion; consistent gains across 22 multimodal benchmarks (**ICML 2026**).
* **Research Intern**, Multimodal Model Team, TeleAI (China Telecom) — Beijing, Oct 2024 – Apr 2025
  * Hierarchical / semantic-guided visual tokenizer for unified multimodal understanding & generation (Emu3 + VQGAN, 3~4× token compression).

Selected Projects
======
* **Brain CT Report Generation & Unified Modeling (UniBCT-Tok)** — BJUT × PKU Third Hospital. Fine-grained cross-modal alignment + pathology knowledge graph; entropy-driven semantic-balanced visual tokenizer (token compression >75%, 44.8% faster inference, SOTA).
* **Noise-Robust Bearing Fault Diagnosis** — BJUT × ANU. Dual-branch LLM adversarial co-evolution; B-CPLX worst-cell accuracy 0.3376 → 0.6909 (+105%).
* **RAG-based Live-Streaming Content Moderation** — BJUT × CETC. ASR/OCR + locally-deployed LLaMA3 with RAG; llama.cpp inference, Docker microservices.

Skills
======
* **Models & Algorithms:** multimodal LLM pretraining & instruction tuning, vision-language representation learning, unified understanding & generation, visual tokenizer design; LoRA / full fine-tuning, INT8 inference, RAG.
* **Frameworks & Engineering:** PyTorch, Hugging Face Transformers, DeepSpeed, vLLM, llama.cpp, Docker; distributed training, data-synthesis pipelines, model serving.
* **AI-assisted Development:** Claude Code, Codex, vibe coding & multi-agent parallel workflows; AI full-stack development experience.
* **Languages:** Python, C++.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* First Prize of Academic Scholarship, 2024–2025.
* First Prize, the 18th China Computer Gaming Championship, 2024.
* First Prize of Academic Scholarship, 2023–2024.
