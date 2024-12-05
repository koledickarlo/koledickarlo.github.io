---
title: 'Enhancing Gaussian Splatting SLAM with Feature-based Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammad Awais
  - "**Karlo Koledić**"
  - Luka Petrović
  - Ivan Marković
# Author notes (optional)
author_notes: ''

date: '2023-12-12T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2312.06021'


# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In International Conference on Automation, Robotics, and Applications (ICARA 2025)
publication_short: ICARA 2025

abstract: Accurate localization and scene reconstruction are essential for the autonomous navigation of mobile agents. Simultaneous Localization and Mapping (SLAM) algorithms address both challenges by formulating a unified optimization problem, offering an integrated solution to both objectives. Recent advances in learning-based scene understanding have significantly improved accuracy and robustness, particularly in adverse scenarios that are troublesome for traditional geometric methods. However, generating an accurate dense scene reconstruction remains an open challenge, largely due to the complexity of the optimization problem, making it unsuitable for real-time requirements on resource-constrained devices. Novel advances in 3D reconstruction such as implicit representations and Gaussian Splatting present an enticing formulation enabling offline reconstruction of large-scale scenes. While these approaches have been successfully adapted for online incremental reconstruction, particularly through Gaussian Splatting SLAM methods, they are hindered by significant computational complexity and convergence challenges due to the non-convex nature of photometric optimization. In this work, we rethink this approach by combining the strengths of traditional feature-based methods with innovative reconstruction capability of Gaussian splatting. Specifically, we integrate feature-based pose estimation, relocalization, and loop closure with 3D Gaussian-based scene reconstruction. This results in state-of-the-art tracking and mapping performance on the EuRoC and TUM datasets, while significantly reducing convergence iterations and improving real-time performance.
# Summary. An optional shortened abstract.
summary: A novel SLAM approach that combines **feature-based pose estimation with Gaussian Splatting** 3D reconstruction, achieving state-of-the-art performance and real-time efficiency on benchmark datasets.

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
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
