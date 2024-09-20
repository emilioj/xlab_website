---
title: "PlayNet: real-time handball play classification with Kalman embeddings and neural networks"
authors:
- omar
- taibo
- emilioj
- jalley
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-08-07T00:00:00Z"
doi: "10.1007/s00371-023-02972-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-07T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The Visual Computer: International Journal of Computer Graphics*"
publication_short: "Vis Comput"

abstract: Real-time play recognition and classification algorithms are crucial for automating video production and live broadcasts of sporting events. However, current methods relying on human pose estimation and deep neural networks introduce high latency on commodity hardware, limiting their usability in low-cost real-time applications.  We present PlayNet, a novel approach to real-time handball play classification. Our method is based on Kalman embeddings, a new low-dimensional representation for game states that enables efficient operation on commodity hardware and customized camera layouts. Firstly, we leverage Kalman filtering to detect and track the main agents in the playing field, allowing us to represent them in a single normalized coordinate space. Secondly, we utilize a neural network trained in non-linear dimensionality reduction through fuzzy topological data structure analysis. As a result, PlayNet achieves real-time play classification with under 55 ms of latency on commodity hardware, making it a promising addition to automated live broadcasting and game analysis pipelines.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf:
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
  caption: 'Overview of the proposed solution'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

