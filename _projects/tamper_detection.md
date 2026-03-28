---
layout: page
title: Camera Tampering Detection
description: A GAN-based approach to securing surveillance infrastructure (Best Paper Award, VISAPP 2019).
img: assets/img/tampering/GAN.png
importance: 5
category: research
related_publications: true
bib_query: tamper_project
---

<div class="award-box mb-4" style="background: rgba(255, 215, 0, 0.1); border-left: 5px solid #ffd700; padding: 15px; border-radius: 5px;">
    <i class="fas fa-trophy" style="color: #d4af37;"></i> 
    <strong>Award:</strong> Received the <strong>Best Paper Award</strong> at the 14th International Conference on Computer Vision Theory and Applications (VISAPP), Prague, 2019.
</div>

Surveillance systems are vulnerable to physical tampering—unauthorized alterations of the camera's viewpoint, defocusing, or masking. Traditional detection methods rely on short-term temporal buffers, which are easily fooled by slow, gradual tampering. This project proposes a **Generative Reference Model** to establish a "ground truth" of normal operating conditions.

### Technical Approach
- **Generative Adversarial Network (GAN):** We trained a GAN to learn the probability density function of images from a specific camera under normal conditions. This allows the system to "sample" a reference image that represents the expected scene at any time.
- **Siamese Network:** To compare the live feed against the generated reference, we employed a Siamese architecture. This network transforms both images into a high-dimensional feature space, maximizing the distance between "normal" and "tampered" states.
- **Deep Learned Features:** By moving away from handcrafted edges or SIFT features, the model achieves higher robustness against environmental noise like rain, snow, or moving shadows.



### Key Results
The proposed method significantly reduces false alarms caused by dynamic backgrounds while maintaining a near-perfect detection rate for abrupt or malicious camera movements.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid 
            path="assets/img/tampering/tamper_detection.png" 
            title="GAN-based Tampering Detection results" 
            class="img-fluid rounded z-depth-1" 
            zoomable=true 
        %}
    </div>
</div>
<div class="caption text-center">
    Overall Framework
</div>

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://www.scitepress.org/Papers/2019/73921/73921.pdf" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-file-pdf"></i> Download Paper
  </a>
</div>