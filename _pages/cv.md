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
* B.S. in Artificial Intelligence (Innovation Class), Dalian University of Technology, 2023 - Present
  * School of Future Technology
  * Major Ranking: 7 / 58
  * English: CET-4 545 / CET-6 548
  * Representative Courses: Probability and Statistics A (100), Optimization Methods (98), Deep Learning (94), Large-Model Technology and Applications (94), Fundamentals of Computer Vision (90), Knowledge Engineering (90)

Research Experience
======
* **First-Author Paper, AAAI 2027 Submission (under double-blind review)**, 2026 - Present
  * *Seeing Through Corneal Reflections: Open-Vocabulary Object Recognition from Corneal Imagery*
  * Proposed an optics-guided prompt synthesis pipeline to build paired synthetic training data, and designed a Degradation-Aware Reflection Enhancement Network (REDA-Net) with scene-guided privileged-context training, forming an iris localization → reflection enhancement → VLM zero-shot open-vocabulary recognition framework.
  * Result: semantic matching accuracy improved from 51.50% to 66.17% on the synthetic benchmark; end-to-end inference latency of **319.89 ms** on Raspberry Pi 5.

Projects
======
* **Bidirectional Multimodal Sign-Language Translation System on RK3588** (Core Member), 2025
  * Built the end-to-end code framework (data collection → keypoint extraction → model inference → visual feedback) for hearing-impaired users on the Rockchip RK3588 platform.
  * Recognition: MediaPipe 21-hand-keypoint extraction, CNN for static gestures, CNN + Transformer for continuous sign-language temporal modeling; Generation: text tokenization mapped to sign-language clips for animation.
  * Deployed on RK3588 ELF2 with NPU acceleration (RKNN), supporting 30+ static gestures and continuous phrases in real time.
  * Award: 2nd Prize (National), 8th National College Embedded Chip & System Design Competition.

* **Crowd-Perception Blind-Assisting System Fusing Smart Cane & Smart Glasses** (Team Leader), 2025
  * Designed a distributed collaborative scheme: smart cane for ground-level hazards, smart glasses for front-view risks; led requirement breakdown and module integration.
  * Cane: YOLOv8 dynamic-object detection + traditional algorithms for structural obstacles (stairs); Glasses: YOLOv5 + optical flow for face recognition; Navigation: Baidu Map + Beidou with yaw replanning; Interaction: multi-level voice-vibration alerts with family-guardian mini-program sync.
  * Deployed on Raspberry Pi 5: 10+ obstacle categories with end-to-end latency under 200 ms.
  * Award: 3rd Prize (National), 2025 China University Computer Competition - AI Creativity Contest.

* **Driver Fatigue Detection & Intelligent Trip Planning with YOLO11 + ViT** (Core Member), 2025
  * Built the edge inference framework: YOLO11 detects face and key regions, ViT models fatigue-related visual features, forming a perception → risk-warning → trip-planning closed loop.
  * Deployed on Huawei Atlas 200I DK with NPU acceleration (CANN / MindSpore Lite), achieving real-time fatigue evaluation at 15+ FPS.
  * Award: 2nd Prize (Provincial), 2025 Ascend AI Innovation Competition.

Awards & Honors
======
* 2nd Prize (National), 8th National College Embedded Chip & System Design Competition (Chip Application Track), Aug 2025
* 3rd Prize (National), 2025 China University Computer Competition - AI Creativity Contest, Nov 2025
* 2nd Prize (Provincial), 2025 Ascend AI Innovation Competition (Liaoning), Dec 2025
* 2nd Prize (International), 2024 APMCM Asia-Pacific Mathematical Contest in Modeling, 2024
* 2nd Prize (Provincial), 2024 Higher Education Press Cup National College Mathematical Contest in Modeling (Liaoning), 2024
* 3rd Prize (Provincial), 7th Global Campus AI Algorithm Elite Competition, 2025
* Silver Award (Provincial), "CCB Cup" Liaoning College Students Innovation Competition, 2025
* 3rd Prize (Provincial), 2025 C4 Network Technology Challenge (Northeast Region), 2025
* Excellence Award, 7th IKCEST "Belt and Road" International Big Data Competition & 11th Baidu-XJTU Big Data Competition, 2025
* Learning Excellence Scholarship (2nd Class), Dalian University of Technology, 2024-2025

Skills
======
* **Languages**: Python, C/C++ (embedded development)
* **Deep Learning & Computer Vision**: CNN, Transformer, ViT, YOLO series (YOLOv5 / YOLOv8 / YOLO11), MediaPipe, vision-language models, open-vocabulary recognition
* **Edge AI Deployment**: RK3588 (RKNN / NPU), Raspberry Pi 5, Huawei Atlas 200I DK (CANN / MindSpore Lite), model conversion and inference optimization
* **Tools**: Git, LaTeX

Service and leadership
======
* Team leader of a national-level competition project (Blind-Assisting System), leading a 3-person team through requirement analysis, architecture design and deployment.
