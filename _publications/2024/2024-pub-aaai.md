---
title:          "Mapping from Meaning: Addressing the Miscalibration of Prompt-Sensitive Language Models"
date:           2024-11-30 00:01:00 +0800
selected:       true
pub:            "Annual AAAI Conference on Artificial Intelligence (AAAI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Poster</span>'
pub_date:       "2024"
semantic_scholar_id: 2357860412  # use this to retrieve citation count
abstract: >-
  An interesting behavior in large language models (LLMs) is prompt sensitivity. When provided with different but semantically equivalent versions of the same prompt, models may produce very different distributions of answers. This suggests that the uncertainty reflected in a model's output distribution for one prompt may not reflect the model's uncertainty about the meaning of the prompt. We model prompt sensitivity as a type of generalization error, and show that sampling across the semantic concept space with paraphrasing perturbations improves uncertainty calibration without compromising accuracy. Additionally, we introduce a new metric for uncertainty decomposition in black-box LLMs that improves upon entropy-based decomposition by modeling semantic continuities in natural language generation. We show that this decomposition metric can be used to quantify how much LLM uncertainty is attributed to prompt sensitivity. Our work introduces a new way to improve uncertainty calibration in prompt-sensitive language models, and provides evidence that some LLMs fail to exhibit consistent general reasoning about the meanings of their inputs.
cover: /assets/images/covers/2024_aaai.png
authors:
  - Kyle Cox
  - Jiawei Xu
  - Yikun Han
  - Rong Xu
  - Tianhao Li
  - Chi-Yang Hsu
  - Tianlong Chen
  - Walter Gerych
  - Ying Ding#
# * is equal contribution
links:
  Paper: /assets/files/papers/2024_aaai.pdf
  Code: https://github.com/xocelyk/paraphrase-uncertainty
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk

---
