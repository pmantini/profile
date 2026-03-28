---
layout: page
title: CQNN 
description: Convolutional Quadratic Neural Networks
img: https://github.com/pmantini/CQNN/raw/master/img.png
importance: 3
category: research
bib_query: cqnn
related_publications: true
---

Standard convolutional neural networks rely on linear transformations followed by an activation function (like ReLU). **CQNN** rethinks this fundamental building block by introducing **Quadratic Neurons**, which inherently capture second-order interactions between input features. 

### Why Quadratic Neurons?
In many computer vision tasks, the decision boundaries are naturally non-linear. By using a quadratic form $y = x^T W x$ as the basic operation, CQNNs can:
- **Increase Model Capacity:** Capture complex patterns with fewer total layers.
- **Improve Decision Boundaries:** Achieve better separation in high-dimensional feature spaces compared to standard linear-based layers.
- **Robust Feature Extraction:** Enhance performance in texture analysis and intricate pattern recognition tasks.

<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0 text-center">
        <img src="https://github.com/pmantini/CQNN/raw/master/img.png" class="img-fluid rounded z-depth-1" alt="UHCTD Synthetic Classes">
    </div>
</div>
<div class="caption text-center">
    Architectural comparison: Standard Convolution vs. Convolutional Quadratic (CQ) layers.
</div>

### Key Contributions
- **Non-Linear Primitives:** Integration of quadratic operations directly into the convolutional framework.
- **Experimental Validation:** Demonstrated superior performance on standard benchmarks for image classification and pattern recognition.
- **Efficiency:** Achieving high accuracy with a more compact representation of non-linearities.

### Resources

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://www.academia.edu/download/91708814/bare_conf.pdf" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-file-pdf"></i> Read Paper (ICPR)
  </a>
  <a href="https://github.com/pmantini/CQNN" class="btn btn-sm z-depth-1" role="button">
    <i class="fab fa-github"></i> Code Repository
  </a>
</div>

---

