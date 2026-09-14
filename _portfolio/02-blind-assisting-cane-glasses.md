---
title: "Crowd-Perception Blind-Assisting System Fusing Smart Cane & Smart Glasses"
excerpt: "Distributed collaborative assistive system for visually-impaired pedestrians: the smart cane handles ground-level hazards while smart glasses handle front-view risks, deployed on Raspberry Pi 5 with 10+ obstacle categories and end-to-end latency under 200 ms. National 3rd Prize, 2025 China University Computer Competition - AI Creativity Contest."
collection: portfolio
---

As the **team leader**, I proposed a distributed collaborative assisting scheme for visually-impaired pedestrians: the **smart cane** handles ground-level risks while the **smart glasses** handle front-view risks. I led requirement decomposition and module coordination, and completed Raspberry Pi 5 deployment with performance tuning.

**Cane side** (ground-level)
- YOLOv8 dynamic-object detection combined with traditional computer-vision algorithms for structural obstacles such as stairs

**Glasses side** (front-view)
- YOLOv5 and optical flow for face recognition and auxiliary scene understanding

**Navigation**
- Baidu Map + Beidou positioning with yaw replanning on deviation

**Interaction**
- Multi-level voice and vibration alert mechanism providing progressive guidance
- Key status synchronized to a family-guardian mini-program

**Result:** real-time detection and graded alerts for **10+ obstacle categories** with end-to-end response latency controlled under **200 ms**.

**Award:** 3rd Prize (National), 2025 China University Computer Competition - AI Creativity Contest.
