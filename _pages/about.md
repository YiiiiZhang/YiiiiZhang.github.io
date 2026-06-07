---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## Research Interests

I focus on **evaluating and exploring capability boundaries of foundation models** in human-centered contexts, particularly in **multilingual, cultural, cognitive, and safety-sensitive reasoning**. My recent work spans:
- **Vision-Language Model (VLM) evaluation** for cultural heritage and visual understanding
- **LLM-brain representation alignment** and narrative comprehension
- **Instruction-following evaluation** for recommendation systems
- **Multimodal learning** for affective computing and collaborative environments

---

## Current Research

**ChinaHeritaQA: A Culturally-Grounded Visual Question Answering Benchmark**  
**May 2025 – Present** | *SODA Lab, LMU Munich*  
*Cross-cultural VLM evaluation, hallucination & factuality analysis*

- Developed a **bilingual VQA benchmark** with 2,279 in-the-wild images and 14,133 Chinese/English QA pairs evaluating VLMs on Chinese UNESCO World Heritage sites
- Evaluated **6 open-weight VLMs** against human baseline, revealing limitations in cultural, historical, functional, and architectural reasoning
- Analyzed failure modes including site confusion, weak image-period/image-function grounding, and cultural bias
- **Status**: First-author work submitted to EMNLP 2026

**Do LLMs Think Like the Brain? LLM–Brain Alignment in Narrative Comprehension**  
**Feb 2025 – May 2025** | *SODA Lab, LMU Munich*  
*LLM embedding extraction, CKA similarity analysis, representation alignment*

- Extracted layer-wise sentence embeddings from multiple LLMs on bilingual *The Little Prince* stimuli
- Implemented CKA-based similarity metrics to compare inter-layer and inter-model representation structures
- Prepared embedding tensors and similarity matrices for downstream alignment with sentence-level fMRI responses
- **Publication**: Yu Lei, Xingyang Ge, **Yi Zhang** et al., *Do Large Language Models Think Like the Brain?*, **AAAI 2026** (Accepted)

---

## Recent Projects

**Audio-Based Depression Detection from Real Counseling Conversations**  
**Nov 2025 – Apr 2026** | *SODA Lab, LMU Munich*  
*Speech processing, Wav2Vec, clinical audio analysis*

- Developed preprocessing pipeline for noisy counseling audio: Wiener denoising, Whisper transcription, speaker diarization, and rule-based patient speech extraction
- Compared MFCC-BiLSTM and Wav2Vec models for depression-related classification (depression, agitation, retardation, HRSD)
- Used SpeechBrain-based emotion profiling to analyze sad/neutral/happy/angry speech distributions across symptom groups
- Identified task boundaries of audio-only modeling through failure analysis on emotion-change regression and EI-stage classification

**Multimodal Emotion Monitoring in Collaborative Learning Environments**  
**Oct 2022 – Sep 2024** | *Beijing Normal University, Zhuhai*  
*Human-centered multimodal learning, affective computing, long-tail classroom data*

- Collected, synchronized, and annotated classroom video/audio data for analyzing student participation and affective states in collaborative settings
- Built multimodal perception pipeline: face detection, identity recognition, and temporal emotion modeling for classroom interaction analysis
- Proposed **MTFNet** (Multi-Scale Transformer Framework) for robust emotion monitoring, achieving **67.5% accuracy on DFEW** dataset
- **Publication**: **Yi Zhang**, et al., *MTFNet: Multi-Scale Transformer Framework for Robust Emotion Monitoring*, **APSIPA ASC 2024** (Accepted, First-author)

**iFLYTEK Algorithm Challenge: Autonomous Driving & Driver Fatigue Detection**  
**May 2022 – Jun 2022**  
*Image classification, facial detection, class imbalance handling*

- Applied data augmentation and trained EfficientNetB7 with Progressive Self-Knowledge Distillation (PS-KD)
- Implemented Test-Time Augmentation (TTA) for robust predictions
- **Result**: **3rd Place**, achieving **99.967% accuracy** on fatigue detection

---

## Publications

### 2026
- Yu Lei*, Xingyang Ge*, **Yi Zhang**, Yiming Yang, Bolei Ma. *Do Large Language Models Think Like the Brain? Sentence-Level Evidence from fMRI and Hierarchical Embeddings*. **AAAI 2026** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:9yKSN-GCB0IC)] [[code](https://github.com/Lucasuuu02/LLM4Brain)]

- **Yi Zhang**, et al. *ChinaHeritaQA: A Culturally-Grounded Visual Question Answering Dataset for World Heritage Sites in China*. **EMNLP 2026** (Under review, First-author). [[huggingface](https://huggingface.co/)] [[paper](https://)]

### 2025
- Chengyan Wu, Bolei Ma, Yihong Liu, Zheyu Zhang, Ningyuan Deng, Yanshu Li, Baolan Chen, **Yi Zhang**, Yun Xue, Barbara Plank. *M-ABSA: A Multilingual Dataset for Aspect-Based Sentiment Analysis*. **EMNLP 2025 Main** (Accepted). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:d1gkVwhDpl0C)] [[huggingface](https://huggingface.co/datasets/Multilingual-NLP/M-ABSA)]

### 2024
- **Yi Zhang**, FangYuan Liu, JiaJia Song, Qi Zeng, Hui He. *MTFNet: Multi-Scale Transformer Framework for Robust Emotion Monitoring in Group Learning Settings*. **APSIPA ASC 2024** (Accepted, First-author). [[paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Lxw9aQ8AAAAJ&citation_for_view=Lxw9aQ8AAAAJ:u-x6o8ySG0sC)] [[code](https://github.com/YiiiiZhang/MTFNet)]

---

## Professional Experience

**Research Assistant – SODA Lab, LMU Munich**  
**Feb 2025 – Present**  
*NLP, LLM fine-tuning, social and cognitive language analysis*

- Contributing to multiple human-centered AI research projects including M-ABSA benchmark construction, LLM4Brain study, and leading ChinaHeritaQA benchmark development
- Managing lab-level HPC access permissions and approval workflows
- Contributing to user guidelines improving efficient use of server storage and computational resources
- Teaching assistant for *Seminar: Natural Language Processing Meets Computational Social Science* — providing technical support and building survey-agent templates for course projects

**Algorithm Engineer Intern – ATA Assessment Technology, Beijing**  
**Jun 2023 – Aug 2023**  
*Computer vision, human detection, pose estimation, deployment-oriented evaluation*

- Processed large-scale real-world dance-assessment data: 100K human detection samples and 1K keypoint samples
- Benchmarked YOLOv8, PP-Detection, MediaPipe, and TinyPose for human detection and pose estimation under practical assessment scenarios
- Improved human detection accuracy by **3%** and keypoint estimation accuracy by **10%**, reducing redundant detections in evaluation pipeline

---

## Education

**Friedrich-Alexander-Universität Erlangen–Nürnberg (FAU), Germany**  
M.Sc. in Data Science | Oct 2024 – Present

- Main area: Machine Learning and Artificial Intelligence
- Coursework: Artificial Intelligence I, Pattern Recognition

**Beijing Normal University, Zhuhai (BNUZ), China**  
B.Eng. in Computer Science and Technology | Sep 2020 – Jun 2024

- Final Grade: **87/100 (Top 5%)**
- Focus: Computer Vision, Emotion Recognition, Deep Learning

---

## Technical Skills

**Machine Learning & Deep Learning**  
Python, C++, PyTorch, Hugging Face Transformers/Datasets, vLLM, scikit-learn

**Computer Vision & NLP**  
YOLOv8, InsightFace, OpenCV, scikit-image, Whisper, SpeechBrain

**Tools & Infrastructure**  
Git, Docker, HPC clusters, LaTeX, Jupyter, WandB

**Languages**  
Chinese Mandarin (Native), English (C1)
