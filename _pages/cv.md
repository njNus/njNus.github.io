---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/cv_nusrot_jahan.pdf)

Education
======
* B.Sc. in Information and Communication Engineering, Bangladesh University of Professionals (BUP), 2025 (CGPA 3.84/4.00)
* Higher Secondary Certificate, Viqarunnisa Noon College, 2020 (GPA 5.00/5.00, Board Scholarship)
* Secondary School Certificate, Ideal School and College, 2018 (GPA 5.00/5.00, Board Scholarship)
* IELTS: Overall Band 7.5 (L 8.0, R 8.0, W 7.0, S 6.5)

Research interests
======
* Interpretable AI for critical decision-making
* Natural Language Processing
* Diffusion interpretability
* Generative AI & Large Language Models (LLMs) in clinical practice

Research experience
======
* **Undergraduate Thesis** (Oct. 2024 – Aug. 2025), *Transformer-Based Suicide Risk Classification from Social Media Text Using Clinically Valid Relabeled and Custom-Generated Dataset* — Supervisor: Dr. Khondokar Habibul Kabir (EEE, IUT)
  * Designed a consensus-driven, dual-model pseudo-labeling pipeline combining a traditional ML ensemble (SVM, RF, Gradient Boosting, LR) with a custom dual-attention transformer (mental-bert-base-uncased) to build an 85,451-post r/SuicideWatch dataset with C-SSRS-mapped four-tier risk labels (High/Moderate/Low/No Risk).
  * Improved label reliability and mitigated class imbalance via cross-model consensus filtering, T5-based clinical paraphrasing, optimized loss functions, and confidence-ranked downsampling.
  * Fine-tuned BERT, DistilBERT, and RoBERTa for balanced accuracy and efficiency, targeting scalable real-time clinical/public-health deployment.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* **Junior Software Engineer**, Integrated Software and Technologies Limited (ISTL) (Mar. 2025 – Aug. 2025)
  * Built enterprise microservices with Spring Boot/Cloud (OAuth 2.0, PostgreSQL, Redis, Kafka, MinIO), including a Product Management System and an aged-care coordination platform with JWT-secured role-based APIs.
  * Completed GIS training across the spatial pipeline: QGIS, PostGIS, GeoServer WMS/WFS, OpenLayers.
* **Intern**, ISTL (Nov. 2024 – Feb. 2025)
  * Developed a secure E-Visa mobile app with biometric authentication (facial recognition, liveliness, fingerprint), Email OTP, and OCR-based NID text extraction.

Skills
======
* **Languages**: C, C++, Python, Java, PHP, Dart
* **Databases**: PostgreSQL, MySQL, Redis, MinIO, PostGIS
* **ML/AI**: TensorFlow, PyTorch, Transformer architectures (Encoder, Decoder, Vision)
* **CV & Biometrics**: OpenCV, Mediapipe, DeepFace, OCR (Pytesseract, EasyOCR, Google Cloud Vision), fingerprint processing
* **Tooling**: Git/GitHub, Docker, VS Code, IntelliJ, Android Studio, LaTeX, MATLAB, CST Studio Suite

Awards & honors
======
* 15th place (team) — 1st Data Innovators Challenge, 40 universities (Oct. 2024)
* 2nd Runner-up — Research-Based Poster Presentation, IEEE BUP SB WIE & Computer Society (Jul. 2023)
* 2nd Runner-up — National Entrepreneurship Summit (2022)
* University merit scholarship (Year 3, Semester 2)
