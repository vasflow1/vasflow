---
layout: default
title: VSSFlow
---

<div class="post">
	<h2 class="pageTitle">VSSFlow:</h2>
	<h2 class="pageTitle">Unifying Video-conditioned Sound and Speech Generation via Joint Learning</h2>
    <p align="center">
	<img src="{{ '/assets/img/teaser.png' | relative_url }}" alt="">
    </p>
    <p align="center">
	<img src="{{ '/assets/img/arch_VASFlow.png' | relative_url }}" alt="">
    </p>
	<p>
Video-conditioned audio generation, encompassing Video-to-Sound (V2S) and Visual Text-to-Speech (VisualTTS), has traditionally been treated as distinct tasks, leaving the potential for a unified generative framework largely underexplored. In this paper, we bridge this gap with VSSFlow, a unified flow-matching framework that seamlessly integrates both tasks. To effectively handle multiple input signals within a Diffusion Transformer (DiT) architecture, we propose a disentangled condition aggregation mechanism leveraging distinct inductive biases of attention layers: cross-attention for semantic conditions and self-attention for temporally-intensive conditions. Besides, contrary to the prevailing belief that joint training for the two tasks leads to performance degradation, we demonstrate that VSSFlow maintains superior performance during end-to-end joint learning process. Furthermore, we use a straightforward feature-level data synthesis method, demonstrating that our framework provides a robust foundation that easily adapts to joint sound and speech generation using purely synthetic data. Extensive experiments on V2S, VisualTTS and joint generation benchmarks show that VSSFlow effectively unifies these tasks and surpasses state-of-the-art domain-specific baselines, underscoring the critical potential of unified generative models. Demos and code can be found in our project page: https://vasflow1.github.io/vasflow/
</p>




