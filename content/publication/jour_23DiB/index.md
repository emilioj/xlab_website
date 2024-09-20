---
title: "A Comprehensive Handball Dynamics Dataset for Game Situation Classification"
authors:
- omar
- taibo
- emilioj
- jalley
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-11-26T00:00:00Z"
doi: "10.1016/j.dib.2023.109848"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Data in Brief*"
publication_short: "Data Br."

abstract: "This article presents a comprehensive dataset of labeled game situations obtained from multiple professional handball matches, which corresponds to the research paper entitled 'PlayNet: Real-time Handball Play Classification with Kalman Embeddings and Neural Networks' https://gac.udc.es/~emilioj/publication/23tvc. The dataset encompasses approximately 11 hours of footage from five handball games played in two different arenas, resulting in around 1 million data frames. Each frame has been meticulously labeled using seven distinct game situation classes (left and right attacks, left and right transitions, left and right penalties, and timeouts). Notably, the dataset does not contain video frames, but provides a synthetic normalized representation of each frame. This representation includes information about player, referee, and ball positions, as well as player and referee velocities, for every labeled game situation. We obtained said details automatically by using an object detector to infer the positions of players, referees, and the ball in each frame. After tracking the detected agent positions across frames, the extracted coordinates underwent normalization through a 'bird's eye' perspective transform, ensuring that the data remained unaffected by variations in camera configurations across different arenas. Finally, a Kalman filter was applied to improve the robustness of player positions and derive their velocities. The labeling process was performed by domain experts employing a custom system designed to annotate game situations, considering the play type and its contextual setting. In conclusion, researchers can utilize this dataset for several purposes: game analysis, automated broadcasting, or game summarization. Furthermore, this dataset can contribute to a broader understanding of the relationship between player dynamics and game situations, shedding light on the level of granularity required for accurately classifying them."

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
  caption: 'Example of each game situation and its representation in our normalized space, with positions represented by blue dots, and velocities by orange vectors'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

