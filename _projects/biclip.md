---
layout: page
title: BiCLIP
description: Domain Canonicalization via Structured Geometric Transformation.
img: https://quantitativeimaginglaboratory.github.io/BilinearCLIP/assets/block_diagram.png # Use your block diagram or a results graph
importance: 1
category: research
bib_query: biclip
related_publications: true
---

BiCLIP addresses the "modality gap" in Vision-Language Models like CLIP and SigLIP. By introducing a structured, bilinear transformation matrix, we achieve state-of-the-art domain adaptation with extreme parameter efficiency.

<div class="video-wrapper" style="text-align: center; margin: 0 auto; display: block;">
    <video autoplay loop muted playsinline class="teaser-video" style="width: 100%; max-width: 640px; border-radius: 8px;">
        <source src="https://quantitativeimaginglaboratory.github.io/BilinearCLIP/assets/biclip.mp4" type="video/mp4">
    </video>
    <p class="caption" style="margin-top: 10px; font-style: italic; color: #555;">
        BiCLIP realigns visual features to the textual manifold.
    </p>
</div>

### Key Highlights
- **SOTA Performance:** +15.2% average improvement over zero-shot CLIP across 11 benchmarks.
- **Extreme Gains:** Up to +42% improvement on specialized domains like EuroSAT.
- **Geometric Insight:** Validates that domain shift can be recovered via canonical transformations.


<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://quantitativeimaginglaboratory.github.io/BilinearCLIP/" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-globe"></i> Project Page
  </a>
  <a href="https://arxiv.org/abs/2603.08942" class="btn btn-sm z-depth-1" role="button">
    <i class="ai ai-arxiv"></i> arXiv
  </a>
  <a href="https://github.com/QuantitativeImagingLaboratory/BilinearCLIP" class="btn btn-sm z-depth-1" role="button">
    <i class="fab fa-github"></i> Code
  </a>
</div>
