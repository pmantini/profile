---
layout: page
title: GeoStack
description: A Framework for Quasi-Abelian Knowledge Composition in VLMs.
img: https://raw.githubusercontent.com/QuantitativeImagingLaboratory/GeoStack/refs/heads/main/docs/assets/intro.png
importance: 1
category: research
bib_query: geostack
related_publications: true
---

GeoStack (Geometric Stacking) addresses the challenge of catastrophic forgetting in Vision-Language Models (VLMs) by allowing independently trained domain experts to be composed into a unified model. By imposing geometric and structural constraints on the adapter manifold, GeoStack ensures the foundational knowledge of the base model remains preserved.

<div class="video-wrapper" style="text-align: center; margin: 0 auto; display: block;">
    <img src="https://raw.githubusercontent.com/QuantitativeImagingLaboratory/GeoStack/refs/heads/main/docs/assets/intro.png" style="width: 100%; max-width: 640px; border-radius: 8px;">
    <p class="caption" style="margin-top: 10px; font-style: italic; color: #555;">
        GeoStack enables modular knowledge composition through geometric constraints.
    </p>
</div>

### Key Highlights
- **Quasi-Abelian Property:** Our framework achieves a quasi-additive composition ($W_g \approx I + \sum \Delta_i$), meaning the order in which you stack domain experts is largely irrelevant.
- **Weight-Folding & Efficiency:** Demonstrates a weight-folding property that achieves constant-time inference complexity $O(1)$, regardless of the number of integrated experts.
- **Mitigating Forgetting:** Significantly outperforms standard adapters in class-incremental learning and multi-domain adaptation.
- **Geometric Stability:** Introduces perturbation minimization theory to ensure the stability of the composed manifold.

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://quantitativeimaginglaboratory.github.io/GeoStack/" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-globe"></i> Project Page
  </a>
  <a href="https://arxiv.org/abs/2605.06477" class="btn btn-sm z-depth-1" role="button">
    <i class="ai ai-arxiv"></i> arXiv
  </a>
  <a href="https://github.com/QuantitativeImagingLaboratory/GeoStack" class="btn btn-sm z-depth-1" role="button">
    <i class="fab fa-github"></i> Code
  </a>
</div>

### Abstract
We address the challenge of knowledge composition in VLMs where accumulating expertise typically leads to catastrophic forgetting. We introduce **GeoStack**, a modular framework that allows independently trained domain experts to be composed into a unified model. By imposing geometric and structural constraints, GeoStack ensures the foundational knowledge of the base model is preserved while enabling constant-time inference.