---
layout: page
title: Image Quality Analysis
description: Evaluating the impact of compression, noise, and artifacts on Deep Learning models.
img: assets/img/quality/4.png
importance: 6
category: research
related_publications: true
bib_query: quality_robustness
---

Most Computer Vision models are trained on "pristine" datasets (like COCO or ImageNet), but real-world surveillance involves transmission lag, heavy H.264/H.265 compression, and sensor noise. This research pillar focuses on quantifying exactly how much "intelligence" we lose when video quality drops.

### Core Research Themes

#### 1. Object Detection under Compression
We evaluated state-of-the-art detectors (YOLOv3, Faster R-CNN, SSD) against varying levels of bit-rate compression. Our findings highlight a critical "cliff" where mAP (mean Average Precision) drops significantly even before the artifacts are highly visible to the human eye.



#### 2. Background Subtraction & Temporal Artifacts
Surveillance often relies on Background Subtraction (BGS) to trigger alerts. We analyze how GOP (Group of Pictures) structures and motion estimation artifacts in compressed video create "ghosting" effects, leading to false positives in abnormality detection pipelines.



### Key Publications
This project encompasses our systematic evaluation of 4 SOTA deep neural network models, showing that existing detectors are highly susceptible to quality distortions stemming from video acquisition.

<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid 
            path="assets/img/quality/1.png" 
            title="Impact of H.264 artifacts on bounding box stability" 
            class="img-fluid rounded z-depth-1" 
            zoomable=true 
        %}
        {% include figure.liquid 
            path="assets/img/quality/3.png" 
            title="Impact of H.264 artifacts on bounding box stability" 
            class="img-fluid rounded z-depth-1" 
            zoomable=true 
        %}
    </div>
</div>
<div class="caption text-center">
    Visualizing how compression artifacts lead to missed detections and bounding box jitter in high-density urban scenes.
</div>

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://www.scitepress.org/Papers/2019/74016/74016.pdf" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-file-pdf"></i> Read Paper (VISAPP)
  </a>
</div>