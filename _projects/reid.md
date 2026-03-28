---
layout: page
title: Robust Person Re-Identification
description: Solving Re-ID challenges in aerial surveillance, occluded scenes, and cloth-changing scenarios.
img: assets/img/reid/reid.png
importance: 2
category: research
related_publications: true
bib_query: reid_robustness
---

Person Re-Identification (Re-ID) is the task of associating images of the same person taken from different cameras. While standard Re-ID has matured, this research focuses on the "In-the-Wild" challenges that prevent deployment in public safety and large-scale urban monitoring.

### Research Focus Areas

#### 1. Aerial & Drone-based Re-ID
Unlike fixed CCTV, aerial imagery involves drastic changes in scale, top-down viewpoints, and fast motion. My work focuses on aligning features between ground-level and aerial perspectives to maintain a continuous chain of identity.



#### 2. Cloth-Changing Re-ID
Traditional Re-ID models rely heavily on color and texture (e.g., "blue shirt"). When a subject changes clothes over multiple days, these models fail. I explore **shape-based and biometric features** that remain invariant to clothing changes, allowing for long-term identity association.

#### 3. Handling Partial Occlusions
In crowded environments (airports, transit hubs), subjects are frequently blocked by pillars, luggage, or other people. We developed mechanisms to dynamically weight visible body parts, ensuring that a partial match is still a reliable match.

