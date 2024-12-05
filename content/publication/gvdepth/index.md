---
title: 'GVDepth: Zero-Shot Monocular Depth Estimation for Ground Vehicles based on Probabilistic Cue Fusion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - name: "Karlo Koledić"
    highlight: true
  - name: "Luka Petrović"
  - name: "Ivan Petrović"
  - name: "Ivan Marković"

# Author notes (optional)
author_notes: ''

date: '2024-12-05T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2312.06021'

weight: 1

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (under review)
publication_short: 'CVPR 2025 (under review)'

abstract: "Generalizing metric monocular depth estimation presents a significant challenge due to its ill-posed nature, while the entanglement between camera parameters and depth amplifies issues further, hindering multi-dataset training and zero-shot accuracy. This challenge is particularly evident in autonomous vehicles and mobile robotics, where data is collected with fixed camera setups, limiting the geometric diversity. Yet, this context also presents an opportunity: the fixed relationship between the camera and the ground plane imposes additional perspective geometry constraints, enabling depth regression via vertical image positions of objects. However, this cue is highly susceptible to overfitting, thus we propose a novel canonical representation that maintains consistency across varied camera setups, effectively disentangling depth from specific parameters and enhancing generalization across datasets. We also propose a novel architecture that adaptively and probabilistically fuses depths estimated via object size and vertical image position cues. A comprehensive evaluation demonstrates the effectiveness of the proposed approach on five autonomous driving datasets, achieving accurate metric depth estimation for varying resolutions, aspect ratios, and camera setups. Notably, we achieve comparable accuracy to existing zero-shot methods, despite training on a single dataset with a single-camera setup."
# Summary. An optional shortened abstract.
summary: "GVDepth leverages novel canonical representation to **disentangle depth from camera parameters**, ensuring consistency across diverse camera setups. Depth is estimated via **probabilistic fusion of intermediate representations** stemming from object size and vertical position cues, achieving accurate and generalizable predictions across multiple datasets and camera configurations. Notably, GVDepth achieves accuracy comparable to SotA zero-shot methods, while **training with a single dataset** collected with a single camera setup."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://gvdepth.github.io/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2312.06021'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.

image:
  placement: 1
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ''

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

