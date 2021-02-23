---
title: Sattelite Pose Estimation
summary: Estimate the relative attitude and position of a known spacecraft. 
tags:
- SPE
date: "2019-06-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/BoChenYS/satellite-pose-estimation
url_code: ""
url_pdf: "https://arxiv.org/pdf/1908.11542.pdf"
url_slides: ""
url_video: https://youtu.be/2hzdLqnvQas

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

Estimating the 6DOF pose of space-borne objects (e.g., satellites, spacecraft, orbital debris) is a crucial step in many space operations such as docking, non-cooperative proximity tasks (e.g., debris removal), and inter-spacecraft communications (e.g., establishing quantum links). Existing solutions are mainly based on active sensor-based systems, e.g., the TriDAR system which uses LiDAR. Recently, monocular pose estimation techniques for space applications are drawing significant attention due to their lower power consumption and relatively simple requirements.

In this project, we propose an approach to estimate the 6DOF pose of a satellite, relative to a canonical pose, from a single image. Our approach combines machine learning and geometric optimisation, by predicting the coordinates of a set of landmarks in the input image, associating the landmarks to their corresponding 3D points on an a priori reconstructed 3D model, then solving for the object pose using non-linear optimisation. Our approach is not only novel for this specific pose estimation task, which helps to further open up a relatively new domain for machine learning and computer vision, but it also demonstrates superior accuracy and won the first place in the recent Kelvins Pose Estimation Challenge organised by the European Space Agency (ESA).
