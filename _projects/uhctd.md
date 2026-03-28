---
layout: page
title: UHCTD 
description: Camera Tampering Dataset. A Comprehensive Dataset for Synthetic Camera Tampering Detection.
img: assets/img/uhctd/fig3.png
importance: 3
category: datasets
bib_query: uhctd
related_publications: true
---

The **University of Houston Camera Tampering Dataset (UHCTD)** is a large-scale resource designed to train and evaluate algorithms for detecting unauthorized or accidental changes in surveillance views. Tampering—whether caused by natural phenomena like sunlight reflection and fog, or malicious human intent like spray painting and lens blocking—compromises the integrity of public safety systems.
<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0 text-center">
        <img src="{{ '/assets/img/uhctd/fig1.png' | relative_url }}" class="img-fluid rounded z-depth-1" alt="UHCTD Synthetic Classes">
    </div>
</div>
<div class="caption text-center">
    Synthetic Data Classes: (a) Original, (b) Covered, (c) Defocussed, and (d) Moved.
</div>


### Dataset Overview
UHCTD features over **26GB of data** captured from two high-resolution outdoor cameras (2048x1536 and 1280x960). We utilized advanced image processing techniques to synthesize three primary categories of tampering into real-world surveillance footage:

- **Covered:** View blocked by objects (cardboard, hands) or natural accumulation (dust, webs).
- **Defocussed:** Blurred views due to lens fogging or intentional focus manipulation.
- **Moved:** Changes in the camera's viewpoint caused by strong winds or manual redirection.

<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0 text-center">
        <img src="{{ '/assets/img/uhctd/fig2.png' | relative_url }}" class="img-fluid rounded z-depth-1" alt="UHCTD Synthetic Classes">
    </div>
</div>
<div class="caption text-center">
    Synthetic Data Classes: (a) Original, (b) Covered, (c) Defocussed, and (d) Moved.
</div>


### Benchmarking
The project includes a comprehensive evaluation of standard deep learning architectures for tampering detection, including:
- **AlexNet**
- **ResNet-18 / ResNet-50**
- **DenseNet-161**

---

### Resources & Development Kits

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://github.com/QuantitativeImagingLaboratory/CTD-Devkit" class="btn btn-sm z-depth-1" role="button">
    <i class="fab fa-github"></i> CTD-Devkit (Training)
  </a>
  <a href="https://github.com/QuantitativeImagingLaboratory/CTD-Evaluation" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-code-branch"></i> Evaluation Code
  </a>
  <a href="https://www.researchgate.net/profile/Pranav-Mantini/publication/334959924_UHCTD_A_Comprehensive_Dataset_for_Camera_Tampering_Detection/links/5d46ffc2299bf1995b662b6d/UHCTD-A-Comprehensive-Dataset-for-Camera-Tampering-Detection.pdf8909852" class="btn btn-sm z-depth-1" role="button">
    <i class="ai ai-ieee"></i> IEEE Xplore
  </a>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLScbxXSo5ZKBJDMAyYs2nkZ6z4NnTeEXfTWEG8AUJmw3f7YQtg/viewform?usp=header" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-file-contract"></i> Dataset Agreement
  </a>
</div>