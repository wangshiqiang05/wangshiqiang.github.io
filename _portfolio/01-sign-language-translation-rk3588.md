---
title: "Bidirectional Multimodal Sign-Language Translation System on RK3588"
excerpt: "End-to-end sign-language recognition and generation system for hearing-impaired users on the Rockchip RK3588 platform, with NPU-accelerated deployment supporting 30+ static gestures and continuous phrases in real time. National 2nd Prize, 8th National College Embedded Chip & System Design Competition."
collection: portfolio
---

As a core member, I designed and implemented the overall code framework of a bidirectional sign-language translation system for hearing-impaired users on the Rockchip RK3588 platform, building a complete end-to-end edge pipeline: **data collection → keypoint extraction → model inference → visual feedback**.

**Recognition side**
- MediaPipe-based extraction of 21 hand keypoints with normalization and feature engineering
- Static gestures: CNN classification
- Continuous sign language: CNN extracts frame-level features, Transformer models temporal dependencies to output phrase results

**Generation side**
- Tokenizes Chinese/English text, maps tokens to sign-language material clips, and stitches them into coherent sign-language animation

**Deployment**
- RK3588 ELF2 development board with NPU inference acceleration (RKNN toolkit)
- Real-time bidirectional translation supporting **30+ static gestures and continuous phrases**

**Award:** 2nd Prize (National), 8th National College Embedded Chip & System Design Competition, 2025.
