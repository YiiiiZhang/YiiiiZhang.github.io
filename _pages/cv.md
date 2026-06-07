---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Friedrich-Alexander-Universität Erlangen–Nürnberg (FAU), Germany**
* M.Sc. in Data Science
* Oct 2024 – Present
* Main area: Machine Learning and Artificial Intelligence
* Coursework: Artificial Intelligence I, Pattern Recognition

**Beijing Normal University, Zhuhai (BNUZ), China**
* B.Eng. in Computer Science and Technology
* Sep 2020 – Jun 2024
* Final Grade: 87/100 (Top 5%)
* Focus: Computer Vision, Emotion Recognition, Deep Learning

## Professional Experience

**Research Assistant – SODA Lab, LMU Munich**
* Feb 2025 – Present
* NLP, LLM fine-tuning, social and cognitive language analysis
  * Contributing to multiple human-centered AI research projects including M-ABSA benchmark construction, LLM4Brain study, and leading ChinaHeritaQA benchmark development
  * Managing lab-level HPC access permissions and approval workflows
  * Contributing to user guidelines improving efficient use of server storage and computational resources
  * Teaching assistant for *Seminar: Natural Language Processing Meets Computational Social Science*

**Algorithm Engineer Intern – ATA Assessment Technology, Beijing**
* Jun 2023 – Aug 2023
* Computer vision, human detection, pose estimation, deployment-oriented evaluation
  * Processed 100K human detection samples and 1K keypoint samples from real-world dance scenarios
  * Benchmarked YOLOv8, PP-Detection, MediaPipe, and TinyPose for practical assessment scenarios
  * Improved human detection accuracy by 3% and keypoint estimation accuracy by 10%

## Research Projects & Benchmarks

**ChinaHeritaQA: A Culturally-Grounded Visual Question Answering Benchmark**
* May 2025 – Present
* Cross-cultural VLM evaluation, factuality, hallucination analysis (First-author work)
  * Developed bilingual VQA benchmark with 2,279 in-the-wild images and 14,133 Chinese/English QA pairs
  * Evaluated 6 open-weight VLMs against human baseline on UNESCO World Heritage sites
  * Analyzed VLM failure modes including same-type site confusion, weak image-to-period grounding, image-to-function grounding, and cultural bias

**LLM–Brain Alignment in Narrative Comprehension**
* Feb 2025 – May 2025
* LLM embedding extraction, CKA similarity analysis
  * Extracted layer-wise sentence embeddings from multiple LLMs on bilingual *The Little Prince* stimuli
  * Implemented CKA-based similarity computation to compare inter-layer and inter-model representation structures
  * Prepared embedding tensors and similarity matrices for downstream alignment with sentence-level fMRI responses

**Multimodal Emotion Monitoring in Collaborative Learning**
* Oct 2022 – Sep 2024
* Human-centered multimodal learning, affective computing, long-tail classroom data (First-author work)
  * Collected, synchronized, and annotated classroom video/audio data
  * Built multimodal perception pipeline with face detection, identity recognition, and temporal emotion modeling
  * Proposed MTFNet framework achieving 67.5% accuracy on DFEW dataset
  * Publication: APSIPA ASC 2024

**Audio-Based Depression Detection from Real Counseling Conversations**
* Nov 2025 – Apr 2026
* Speech processing, Wav2Vec, clinical audio analysis
  * Developed preprocessing pipeline for noisy counseling audio using Wiener denoising, Whisper transcription, speaker diarization
  * Compared MFCC-BiLSTM and Wav2Vec models for depression-related classification with subject-level split and class-balanced loss
  * Used SpeechBrain-based emotion profiling to analyze speech distributions across clinical symptom groups
  * Identified task boundaries through failure analysis on emotion-change regression and EI-stage classification

## Technical Skills

**Machine Learning & Deep Learning**
* Python, C++, PyTorch, Hugging Face Transformers/Datasets, vLLM, scikit-learn

**Computer Vision & NLP**
* YOLOv8, InsightFace, OpenCV, scikit-image, Whisper, SpeechBrain

**Tools & Infrastructure**
* Git, Docker, HPC clusters, LaTeX, Jupyter, WandB

**Languages**
* Chinese Mandarin (Native), English (C1)

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
