---
title: "CCDD: Concept-Consistent Diffusion Denoising"
excerpt: "<b>Ongoing Research.</b><br/>Exploring interpretability and control in generative diffusion models.<br/><img src='/images/ccdd_banner.png'>"
collection: portfolio
date: 2025-11- Now
order: 1
---

## Project Description
Concept-Consistent Diffusion Denoising (CCDD) is an ongoing research initiative focusing on the interpretability and controllability of Diffusion Models. We are investigating how to maintain semantic consistency during the denoising process.

## Current Progress
*   **Data Pipeline:** Built a pipeline using **SAM2** for segmentation and **CLIP** for embedding to generate fine-grained concept clusters from the CIFAR-10/CUB datasets.
*   **Methodology:** utilizing K-Means clustering to extract semantic concepts and injecting them into the diffusion reverse process to guide generation.
*   **Initial Results:** Preliminary experiments show promising results in controlling the generation of specific attributes while maintaining high image fidelity.

## Future Work
*   Optimizing the `pos_weight` mechanism to handle class imbalance in concept datasets.
*   Extending the framework to large-scale datasets like ImageNet.

<!-- ![Initial Results](/images/ccdd_results.png)
*Figure 1: Preliminary generation results controlled by specific concepts.* -->
