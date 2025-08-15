---
layout: default
title: VASFlow
---

<div class="post">
	<h2 class="pageTitle">VASFlow:</h2>
	<h2 class="pageTitle">Boosting Video-conditioned Audio and Speech Generation via Joint Training</h2>
    <p align="center">
	<img src="{{ '/assets/img/teaser.png' | relative_url }}" alt="">
    </p>
    <p align="center">
	<img src="{{ '/assets/img/arch_VASFlow.png' | relative_url }}" alt="">
    </p>
	<p>
Video-conditioned audio and speech generation, encompassing video-to-audio (V2A) and visual text-to-speech (visualTTS), are rapidly evolving research fields. While unified generative models are becoming a trend due to their versatility and scalability, existing approaches still rely on complex, domain-specific architectures to handle different tasks. To address this challenge and explore the mutual influence of these two tasks, we propose, the first end-to-end framework for integrated Video-conditioned Audio and Speech generation. Leveraging Flow matching method and Diffusion Transformers (DiT) as the denoising backbone, VASFlow unifies both tasks within a streamlined and efficient architecture. We systematically investigate different mechanisms to incorporate audio and speech conditions into DiT blocks, demonstrating that concatenating speech features with latent representations and integrating video features via cross-attention layers optimizes performance and speed up convergence for the two tasks. Furthermore, rigorous experiments reveal that joint training with audio and speech data does not cause mutual interference, instead significantly enhances performance, particularly for audio generation. Extensive evaluations show that VASFlow matches or surpasses state-of-the-art domain-specific baselines on V2A and visualTTS benchmarks, providing new insights into audio-speech synergy and underscoring the value of unified generative models.




