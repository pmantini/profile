---
layout: page
title: Video Pipeline Framework 
description: Methods and systems for customized image and video analysis.
img: assets/img/pipelines/pipeline.png
importance: 5
category: software & patents
bib_query: pipelines
related_publications: true
---

**Aware AI** is a design framework created to solve the "Black Box" problem in video surveillance. While most computer vision algorithms are trapped in rigid, non-customizable software, Aware AI transitions the power to build and perform analytics from the researcher to the end-user through a **Streamline Processing Framework.**

### The Core Problem: The Research-User Disconnect
Most vision algorithms fail in the real world due to:
- **Data & Scene Variability:** Algorithms optimized on static datasets struggle with real-world shifts in lighting and density.
- **Limited Models:** Users lack the tools to retrain or adapt models for specific tasks without a developer.

### Technical Architecture: The Vision Pipeline
The framework treats analytics as a series of non-blocking, unit-processing blocks called **Modules**. These are connected via a **Publish/Subscribe service** to form dynamic pipelines.

- **Initialization Stage:** Fetches streams, loads weights, and prepares the compute environment.
- **Processing Stage:** Handles the heavy lifting through **Source** (data generation), **Process** (inference/logic), and **Sink** (output/storage) modules.
- **Termination Stage:** Finalizes operations, such as database uploads or triggering external alerts.


### Scalability via Kubernetes & Containers
To handle large-scale camera networks, the framework is implemented as a **containerized cluster**:
- **K8s Orchestration:** Each pipeline is deployed as a logical unit in a Kubernetes cluster, sharing networking and storage resources.
- **Microservices Approach:** Individual modules (e.g., an MCNN crowd density estimator or an SSD object detector) are isolated as containers, ensuring that failed modules are automatically restarted without killing the entire pipeline.
- **Distributed Pub/Sub:** Allows modules to be deployed across different compute nodes while maintaining real-time communication.



### Real-World Use Cases
The Aware AI software features a "Design Analytics" interface where users can drag and drop modules to create custom logic:
1.  **Crowd Counting Alert:** Combines an MCNN density module with a thresholding module to generate riots/protest alerts.
2.  **No Parking Enforcement:** Chains an object detector, a class filter (for cars), and a spatial ROI filter to detect persistent parking violations in restricted zones.

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <a href="https://patents.google.com/patent/US11532158B2/en" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-desktop"></i> Patent
  </a>
  
</div>

