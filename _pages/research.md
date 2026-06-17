---
layout: page
title: "Research"
permalink: /research/
---

## Research Interests

My research focuses on evaluating and exploring the capability boundaries of foundation models in human-
centered contexts, particularly multilingual, cultural, cognitive, and safety-sensitive reasoning. My recent
work spans VLM evaluation for cultural heritage question answering and LLM–brain representation alignment,
and my ongoing research examines instruction-following evaluation for dietary recommendation models.

---

## Research Experience

**ChinaHeritaQA: Culturally-Grounded VQA Benchmark** *(First-author, EMNLP 2026 under review)*   
**May 2025 – Present** | SODA Lab, LMU Munich

We developed  a bilingual VQA benchmark with 2,279 in-the-wild images and 14,133 Chinese/English QA pairs to evaluate VLM limitations in cultural, historical, functional, and architectural reasoning on Chinese UNESCO World Heritage sites.Evaluated six open-weight VLMs against a human baseline, revealing that strong visual recognition does not reliably transfer to historical, functional, and architectural reasoning. [[paper](https://arxiv.org/abs/2606.08959)][[Huggingface](https://huggingface.co/datasets/Multilingual-NLP/ChinaHeritaQA)]

**LLM--Brain Alignment in Narrative Comprehension**   
**May 2025 – Dec 2025** | SODA Lab, LMU Munich

We developed a computational workflow aligning LLMs with fMRI data using layer-wise sentence embeddings (The Little Prince) and CKA similarity analysis. Results revealed that intermediate LLM layers best match human brain activations, and advanced models exhibit 'brain-like' semantic hierarchies, indicating shared language processing mechanisms.

**Audio-Based Depression Detection from Real Counseling Conversations**  
**Nov 2025 – Mar 2026** | MDA Lab, Erlangen-Nurmberg University

Depression leaves traces in speech—pacing, tone, and word choice. I'm building models that extract these signals from real, noisy counseling conversations. The challenge isn't just processing audio (Whisper + speaker diarization), but understanding the limits: audio alone struggles with mood fluctuations and complex clinical stages, highlighting where multimodal approaches become necessary.

**Multimodal Emotion Monitoring in Collaborative Learning**   
**Oct 2022 – Sep 2024** | [Prof. HuiHe](https://fas.bnu.edu.cn/jyjg/xsgk/sjkxydsjjsx1/xsszsjkx/sjkxydsjjsxfx1/4a9e8fa035924c6298dd0ee8d73273e0.htm), BNU

In this project, I was responsible for the entire workflow, from data collection, cleaning and processing, through to model architecture selection and development, and finally the application of the results. We collected a large volume of raw video footage of group collaborative learning from real-world classrooms. We then collaborated with [Prof. Zengqi](https://fe.bnu.edu.cn/pc/cms1info/resume/50/226)'s team to identify the emotional features and categories necessary for understanding student states within an educational setting. Ultimately, we built a multimodal perception pipeline incorporating face detection, identity recognition, and temporal emotion modelling for real-world classroom interaction analysis.
---

## Publications & Preprints

**2026**

- **Yi Zhang\*** Bolei Ma*, et al. *ChinaHeritaQA: A Culturally-Grounded Visual Question Answering Dataset for World Heritage Sites in China*. **EMNLP 2026 (Under review, First-author)**.

- Yu Lei*, Xingyang Ge*, **Yi Zhang**, et al. *Do Large Language Models Think Like the Brain? Sentence-Level Evidence from fMRI and Hierarchical Embeddings*. **AAAI 2026** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:9yKSN-GCB0IC)] [[code](https://github.com/Lucasuuu02/LLM4Brain)]

**2025**

- Chengyan Wu, Bolei Ma, et al., **Yi Zhang**, et al. *M-ABSA: A Multilingual Dataset for Aspect-Based Sentiment Analysis*. **EMNLP 2025 Main** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:d1gkVwhDpl0C)] [[dataset](https://huggingface.co/datasets/Multilingual-NLP/M-ABSA)]

**2024**

- **Yi Zhang**, FangYuan Liu, JiaJia Song, Qi Zeng, Hui He. *MTFNet: Multi-Scale Transformer Framework for Robust Emotion Monitoring in Group Learning Settings*. **APSIPA ASC 2024** (First-author). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:u-x6o8ySG0sC)] [[code](https://github.com/YiiiiZhang/MTFNet)]

---
## Competition
**Driver Fatigue Detection Challenge** — *3rd Place*  
**May 2022 – Jun 2022**

Combining data augmentation with EfficientNetB7 and test-time augmentation, I achieved 99.97% accuracy on driver fatigue classification—an exercise in practical computer vision under real-world constraints.
