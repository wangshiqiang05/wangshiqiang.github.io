---
title: "Seeing Through Corneal Reflections: Open-Vocabulary Object Recognition from Corneal Imagery"
collection: publications
category: preprints
permalink: /publication/corneal-reflections
excerpt: 'First-author paper under review at AAAI 2027. Proposes an optics-guided prompt synthesis pipeline and a Degradation-Aware Reflection Enhancement Network (REDA-Net) with scene-guided privileged-context training for zero-shot open-vocabulary recognition from corneal reflection images. Semantic-match accuracy: 51.50% → 66.17%; end-to-end latency: 319.89 ms on Raspberry Pi 5.'
date: 2026-09-08
status: "Under Review at AAAI 2027"
---

The human cornea naturally reflects the surrounding scene, providing an unobtrusive modality for ambient perception. However, corneal reflections are severely degraded by iris texture interference, spherical distortion, motion blur, and optical attenuation, making direct semantic recognition highly unreliable.

We propose a unified framework comprising:

1. **Optics-guided prompt synthesis pipeline** – injects corneal optical priors into a generative model to construct a paired synthetic dataset of degraded and clear corneal reflections;
2. **Degradation-Aware Reflection Enhancement Network (REDA-Net)** – trained with scene-guided privileged-context training, where paired scene images guide the contextual stream only during training, while inference requires only duplicated degraded reflections;
3. **Open-vocabulary object recognition** – a vision-language model performs zero-shot open-vocabulary recognition on the enhanced reflection.

On the controlled synthetic benchmark, the framework increases semantic-match accuracy from 51.50% to 66.17% over direct VLM inference on degraded reflections, while maintaining an end-to-end inference latency of **319.89 ms** on edge devices. To our knowledge, this is the first systematic framework for direct open-vocabulary object recognition from human eye images.
