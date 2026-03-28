---
layout: about
title: about
permalink: /
subtitle: Dept. of Computer Science, <a href='http://www.uh.edu'>UH</a>

profile:
  align: left
  image: pranav_profile.jpg
  image_circular: false # crops the image to make it circular
  # address: >
  #   <p>University of Houston</p>
  #   <p>Houston, TX</p>
  more_info: >
      <p>Senior Researcher & Lecturer</p>      
      <p>Office: PGH 524</p>
      <p>University of Houston</p>
      <p>Houston, TX</p>


announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
selected_projects: true

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---

I’m a Senior Researcher and Lecturer at the University of Houston, where I’ve been teaching and researching since 2017. My research spans Computer Vision, Image Processing, and Machine Learning. 

I design intelligent tools for public safety video systems, bridging theoretical research with robust, real-world deployment. My research addresses foundational challenges in person re-identification, anomaly detection, and neural network architectures. My work has been recognized with a U.S. Patent, best-paper awards, and significant federal grant funding.

Currently, I'm excited about exploring geometries and frameworks for parameter-efficient fine-tuning of Contrastive Vision Language Models.



<!-- <div class="projects-featured mt-5">
  <h2>featured research</h2>
  <hr>
  <div class="container">
    <div class="row">
      {% assign featured_projects = site.projects | sort: "importance" %}
      {% for project in featured_projects limit: 3 %}
      <div class="col-md-4 mb-4">
        <a href="{{ project.url | relative_url }}">
          <div class="card h-100 z-depth-1 hoverable">
            {% if project.img %}
              <img src="{{ project.img | relative_url }}" class="card-img-top" alt="{{ project.title }}">
            {% endif %}
            <div class="card-body">
              <h5 class="card-title">{{ project.title }}</h5>
              <p class="card-text" style="font-size: 0.9rem;">{{ project.description }}</p>
            </div>
          </div>
        </a>
      </div>
      {% endfor %}
    </div>
  </div>
  <div class="text-right">
    <a href="{{ '/projects/' | relative_url }}" class="btn btn-sm btn-outline-primary">View All Projects &rarr;</a>
  </div>
</div> -->