---
layout: page
title: ADOC
description: A Day on Campus Dataset. An Anomaly Detection Dataset for Events in a Single Camera.
img: assets/img/adoc/a_mobility_scooter.gif  # Use an image of a golf cart or conversation event
importance: 2
category: datasets
bib_query: adoc
related_publications: true
---


<h3 class="mt-4">Anomaly Event Examples</h3>
<p class="mb-4">Visual examples from the ADOC dataset showing diverse events under varying conditions.</p>

<div class="container adoc-matrix" style="padding: 0;">
  <div class="row text-center mt-3">
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_golf_cart.gif' | relative_url }}" alt="Golf Cart Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Golf Cart on Walkway</p>
      </div>
    </div>
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_person_on_grass.gif' | relative_url }}" alt="Person on Grass Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Person on Grass</p>
      </div>
    </div>
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_person_skate.gif' | relative_url }}" alt="Skateboard Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Person on Skateboard</p>
      </div>
    </div>
  </div>

  <div class="row text-center">
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_having_conv.gif' | relative_url }}" alt="Conversation Event" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Having a Conversation</p>
      </div>
    </div>
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_person_riding_bike.gif' | relative_url }}" alt="Bike Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Riding Bike (Day)</p>
      </div>
    </div>
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_umbrella.gif' | relative_url }}" alt="Umbrella Event" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Person with Umbrella</p>
      </div>
    </div>
  </div>

  <div class="row text-center justify-content-center">
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_mobility_scooter.gif' | relative_url }}" alt="Mobility Scooter Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Mobility Scooter</p>
      </div>
    </div>
    <div class="col-sm-4 mb-3">
      <div class="gif-card z-depth-1 rounded">
        <img src="{{ '/assets/img/adoc/a_person_riding_bike_n.gif' | relative_url }}" alt="Night Bike Anomaly" class="img-fluid rounded">
        <p class="caption mt-2 mb-2">Riding Bike (Night)</p>
      </div>
    </div>
  </div>
</div>


The **ADOC** dataset is a foundational resource for anomaly detection in single-camera surveillance. We acquired 24 continuous hours of 1080p, H.264 video from a live university campus. The data encapsulates extreme variations in illumination, background clutter, and crowd density.

We define anomalies as statistically "rare" events (low-frequency occurrences). Our data is meticulously annotated with **875 events**, including high-frequency actions and specific rare activities like "golf cart on walkway" or "person with a mobility scooter."


### Selected Anomaly Events

| Event Name | Frequency |
| :--- | :--- |
| **Person riding a bike** | 238 |
| **Person on grass** | 132 |
| **Golf cart on walkway** | 105 |
| **Having a conversation** | 58 |
| **Person on skateboard** | 48 |


### Project Resources

<div class="project-links" style="text-align: center; margin-top: 20px;">
  <!-- <a href="https://github.com/QuantitativeImagingLaboratory/ADOC-Dataset" class="btn btn-sm z-depth-1" role="button">
    <i class="fab fa-github"></i> Project Repo
  </a> -->
  <a href="http://openaccess.thecvf.com/content/ACCV2020/papers/Pranav_A_Day_on_Campus_-_An_Anomaly_Detection_Dataset_for_ACCV_2020_paper.pdf" class="btn btn-sm z-depth-1" role="button">
    <i class="ai ai-arxiv"></i> CVF Paper
  </a>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLSfodLeFW_ndiW_LdAWMtdDWRB0pEw6SIgEMjnKRx9Gmtsgopg/viewform?usp=preview" class="btn btn-sm z-depth-1" role="button">
    <i class="fas fa-file-signature"></i> Download Agreement
  </a>
</div>
