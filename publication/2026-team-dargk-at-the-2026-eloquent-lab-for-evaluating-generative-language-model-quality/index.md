+++
title = "Team DArgk at the 2026 ELOQUENT lab for evaluating generative language model quality: Residuals of Humanity: AI Detection Evasion via GRPO Fine-Tuning: Notebook for the Voight-Kampff Task on Eloquent Lab 2026 at CLEF 2026"
date = "2026-09-21"
authors = ["Antonela Tommasel", "Juan Manuel Rodriguez"]
publication_types = ["1"]
publication = "_CLEF 2026 Working Notes, September 21–24, 2026, Jena, Germany_"
publication_short = "_CLEF 2026 Working Notes, Jena, Germany_"
abstract = "Large language models (LLMs) can generate fluent and coherent text that is increasingly difficult to distinguish from human writing, motivating the development of automatic AI-generated text detectors. However, the robustness of such detectors under adversarial generation remains uncertain. This paper presents SHADE (Stochastic Human-like generation via Adversarial Detector Evasion), a reinforcement learning framework that formulates detector evasion as a policy optimization problem. Instead of applying post-hoc perturbations or prompting-based rewriting, SHADE fine-tunes an instruction-tuned LLaMA model with Group Relative Policy Optimization (GRPO), using feedback from a surrogate detector based on the PAN 2025 mdok system. Our experiments show that full fine-tuning with a small KL regularization penalty achieves 98.5% surrogate evasion, compared to 1.5% for the base model, while LoRA-based adaptation is substantially less effective under regularization. Linguistic analysis reveals that successful evasion is associated with shorter, simpler, and less lexically diverse outputs, suggesting that high detector evasion does not necessarily correspond to more human-like writing. In the official Voight-Kampff competition setting, our submissions ranked sixth and seventh, indicating that optimization against a single surrogate detector only partially transfers to unseen evaluation classifiers. These results highlight both the potential and limitations of reinforcement learning for adversarial AI-text generation and motivate more robust, multi-detector evaluation protocols for AI-generated text detection."
summary = "This paper presents SHADE, a GRPO-based adversarial fine-tuning approach that strongly improves evasion of a surrogate AI-text detector but transfers only partially to unseen detectors."
image_preview = ""
selected = false
projects = []
tags = []
url_pdf = "2026-team-dargk-at-the-2026-eloquent-lab-for-evaluating-generative-language-model-quality.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://clef-staging.pages.dev/paper109.pdf"
math = true
highlight = true
[header]
image = ""
caption = ""
+++
