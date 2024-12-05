---
title: 'MOFT: Monocular odometry based on deep depth and careful feature selection and tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - "**Karlo Koledić**"
  - Igor Cvišić
  - Ivan Marković
  - Ivan Petrović
# Author notes (optional)
author_notes: ''

date: '2023-05-29T00:00:00Z'
doi: '10.1109/ICRA48891.2023.10160588'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation* (ICRA 2023)
publication_short: ICRA 2023

abstract: Autonomous localization in unknown environments is a fundamental problem in many emerging fields and the monocular visual approach offers many advantages, due to being a rich source of information and avoiding comparatively more complicated setups and multisensor calibration. Deep learning opened new venues for monocular odometry yielding not only end-to-end approaches but also hybrid methods combining the well studied geometry with specific deep components. In this paper we propose a monocular odometry that leverages deep depth within a feature based geometrical framework yielding a lightweight frame-to-frame approach with metrically scaled trajectories and state-of-the-art accuracy. The front-end is based on a multihypothesis matcher with perspective correction coupled with deep depth predictions that enables careful feature selection and tracking; especially of ground plane features that are suitable for translation estimation. The back-end is based on point-to-epipolar line minimization for rotation and unit translation estimation, followed by deep depth aided reprojection error minimization for metrically correct translation estimation. Furthermore, we also present a domain shift adaptation approach that allows for generalization over different camera intrinsic and extrinsic setups. The proposed approach is evaluated on the KITTI and KITTI-360 datasets, showing competitive results and in most cases outperforming other state-of-the-art stereo and monocular methods.
# Summary. An optional shortened abstract.
summary: A lightweight monocular odometry method that **combines deep depth predictions with a feature-based geometrical framework**, achieving metrically scaled trajectories, state-of-the-art accuracy, and robust generalization across different camera setups, as demonstrated on KITTI and KITTI-360 datasets.

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
url_source: 'https://ieeexplore.ieee.org/abstract/document/10160588'
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
