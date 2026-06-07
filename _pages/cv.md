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

* **M.Sc. in Data Science** — Friedrich-Alexander-Universität Erlangen–Nürnberg (FAU), Germany | Oct 2024 – Present
  * Focus: Machine Learning and Artificial Intelligence
  * Coursework: Artificial Intelligence I, Pattern Recognition

* **B.Eng. in Computer Science & Technology** — Beijing Normal University, Zhuhai (BNUZ), China | Sep 2020 – Jun 2024
  * Final Grade: 87/100 (Top 5%)
  * Focus: Computer Vision, Emotion Recognition, Deep Learning

## Work Experience

* **Research Assistant** — SODA Lab, LMU Munich | Feb 2025 – Present
  * Lead development of ChinaHeritaQA benchmark (first-author work submitted to EMNLP 2026)
  * Contribute to human-centered AI projects: M-ABSA multilingual dataset, LLM4Brain study
  * Teaching assistant for *Seminar: Natural Language Processing Meets Computational Social Science*
  * Manage lab infrastructure: HPC access, resource allocation, documentation

* **Algorithm Engineer Intern** — ATA Assessment Technology, Beijing | Jun 2023 – Aug 2023
  * Benchmarked YOLOv8, PP-Detection, MediaPipe, TinyPose on 100K+ dance assessment samples
  * Improved human detection by 3%, pose estimation by 10% through systematic optimization
  * Deployed models for real-world assessment scenarios

## Research & Projects

* **ChinaHeritaQA: Culturally-Grounded VQA Benchmark** *(First-author, EMNLP 2026 under review)* | May 2025 – Present
  * 2,279 real-world images, 14,133 bilingual Q&A pairs on Chinese UNESCO World Heritage sites
  * Evaluated 6 open-weight VLMs; revealed perception-reasoning gap in cultural/historical tasks
  * Analyzed failure modes: site confusion, weak grounding, cultural bias

* **LLM–Brain Alignment in Narrative Comprehension** *(Co-author, AAAI 2026 accepted)* | Feb 2025 – May 2025
  * Extracted layer-wise embeddings from multiple LLMs on bilingual *Little Prince* passages
  * Computed CKA similarity metrics between LLM representations and fMRI brain scans
  * Found alignment in representational structures between neural networks and human brain

* **Audio-Based Depression Detection** *(In progress)* | Nov 2025 – Apr 2026
  * Built preprocessing pipeline for noisy counseling audio (denoising, transcription, diarization)
  * Compared MFCC-BiLSTM and Wav2Vec models with subject-level splits and class-balanced loss
  * Identified task boundaries: audio-only struggles with mood changes and complex clinical stages

* **MTFNet: Emotion Monitoring in Collaborative Learning** *(First-author, APSIPA ASC 2024)* | Oct 2022 – Sep 2024
  * Collected and synchronized classroom video/audio data for real collaborative sessions
  * Built multi-scale transformer framework: 67.5% accuracy on DFEW emotion dataset
  * Analyzed student participation and affective states in group learning

* **Driver Fatigue Detection Challenge** | May 2022 – Jun 2022
  * Achieved 99.97% accuracy using EfficientNetB7 with PS-KD and test-time augmentation
  * **3rd Place** in iFLYTEK competition

## Technical Skills

* **ML/DL**: Python, C++, PyTorch, Hugging Face (Transformers/Datasets), vLLM, scikit-learn
* **Vision/Audio**: YOLOv8, InsightFace, OpenCV, scikit-image, Whisper, SpeechBrain
* **Tools**: Git, Docker, HPC, LaTeX, Jupyter, WandB
* **Languages**: Chinese Mandarin (Native), English (C1)

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
