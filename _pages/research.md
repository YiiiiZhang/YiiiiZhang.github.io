---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Research Interests

I investigate **how foundation models reason across languages, cultures, and human cognition**. My work bridges AI evaluation with real-world impact:

- **Cross-cultural VLM evaluation**: Understanding why models fail on cultural and historical reasoning despite strong visual recognition. This work has implications for deploying vision systems in diverse global contexts.

- **LLM-brain alignment**: Exploring how neural networks encode meaning similarly to human brain representations. By comparing layer-wise embeddings with fMRI data, we can understand what computational structures emerge when models learn language.

- **Affective computing in education**: Building multimodal systems that recognize and respond to student emotions in collaborative settings. Emotions drive learning, and understanding them helps create better educational technologies.

---

## Current Research

**ChinaHeritaQA: Culturally-Grounded VQA Benchmark** *(First-author, EMNLP 2026 under review)*  
**May 2025 – Present** | SODA Lab, LMU Munich

I'm developing a bilingual benchmark with 2,279 real-world images of Chinese UNESCO World Heritage sites and 14,133 Q&A pairs to understand why state-of-the-art vision models fail when reasoning about culture and history. Even models with strong visual recognition stumble on questions about historical periods, architectural functions, and cultural significance. This work reveals a critical gap between perception and reasoning that current VLMs haven't bridged. [[code & data](https://huggingface.co/)]

**Audio-Based Depression Detection** *(In progress)*  
**Nov 2025 – Apr 2026** | SODA Lab, LMU Munich

Depression leaves traces in speech—pacing, tone, and word choice. I'm building models that extract these signals from real, noisy counseling conversations. The challenge isn't just processing audio (Whisper + speaker diarization), but understanding the limits: audio alone struggles with mood fluctuations and complex clinical stages, highlighting where multimodal approaches become necessary.

---

## Publications & Preprints

**2026**

- Yu Lei*, Xingyang Ge*, **Yi Zhang**, et al. *Do Large Language Models Think Like the Brain? Sentence-Level Evidence from fMRI and Hierarchical Embeddings*. **AAAI 2026** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:9yKSN-GCB0IC)] [[code](https://github.com/Lucasuuu02/LLM4Brain)]

- **Yi Zhang** et al. *ChinaHeritaQA: A Culturally-Grounded Visual Question Answering Dataset for World Heritage Sites in China*. **EMNLP 2026** (Under review, First-author).

**2025**

- Chengyan Wu, Bolei Ma, et al., **Yi Zhang**, et al. *M-ABSA: A Multilingual Dataset for Aspect-Based Sentiment Analysis*. **EMNLP 2025 Main** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:d1gkVwhDpl0C)] [[dataset](https://huggingface.co/datasets/Multilingual-NLP/M-ABSA)]

**2024**

- **Yi Zhang**, FangYuan Liu, JiaJia Song, Qi Zeng, Hui He. *MTFNet: Multi-Scale Transformer Framework for Robust Emotion Monitoring in Group Learning Settings*. **APSIPA ASC 2024** (First-author). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:u-x6o8ySG0sC)] [[code](https://github.com/YiiiiZhang/MTFNet)]

---

## Selected Past Projects

**MTFNet: Recognizing Emotions in Classroom Collaboration** *(First-author, APSIPA ASC 2024)*  
**Oct 2022 – Sep 2024** | Beijing Normal University, Zhuhai

Teaching happens through faces, voices, and body language. I collected and analyzed synchronized classroom video/audio from real collaborative learning sessions, building a multi-scale transformer model that achieves 67.5% accuracy detecting emotional states—critical for understanding student engagement in group work.

**Driver Fatigue Detection Challenge** — *3rd Place*  
**May 2022 – Jun 2022**

Combining data augmentation with EfficientNetB7 and test-time augmentation, I achieved 99.97% accuracy on driver fatigue classification—an exercise in practical computer vision under real-world constraints.
