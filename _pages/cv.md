---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Electronics and Communication Engineering, Gujarat Technological University, Ahmedabad, India (ongoing)
* M.Tech. in Electronics and Communication Engineering, Gujarat Technological University, Ahmedabad, India

Research Interests
======
* Speaker Diarization (who spoke when)
* Speaker Embeddings and Robust Feature Learning
* Deep Learning for Speech and Audio Processing
* Adaptive Neural Architectures (TDNN, x-vector, AFA-TDNN)
* Edge AI and Lightweight Models for IoT Devices
* Data Augmentation for Acoustic Robustness

Technical Skills
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Programming**: Python, MATLAB
* **Deep Learning Frameworks**: PyTorch, TensorFlow, Keras
* **Speech Toolkits**: Kaldi, SpeechBrain, pyannote-audio
* **Audio Processing**: librosa, SciPy, soundfile
* **Other Tools**: Git, Linux, Docker, Jupyter

Service
======
* Reviewer for international conferences and journals in speech and audio processing
