+++
title = "A Comprehensive Handball Dynamics Dataset for Game Situation Classification"
date = 2023-11-26
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Omar A. Mures", "Javier Taibo", "Emilio J. Padrón", "Jose A. Iglesias-Guitian"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Data in Brief*."
publication_short = "In *Data Br.*"

# Abstract and optional shortened version.
abstract = "This article presents a comprehensive dataset of labeled game situations obtained from multiple professional handball matches, which corresponds to the research paper entitled 'PlayNet: Real-time Handball Play Classification with Kalman Embeddings and Neural Networks' https://gac.udc.es/~emilioj/publication/23tvc. The dataset encompasses approximately 11 hours of footage from five handball games played in two different arenas, resulting in around 1 million data frames. Each frame has been meticulously labeled using seven distinct game situation classes (left and right attacks, left and right transitions, left and right penalties, and timeouts). Notably, the dataset does not contain video frames, but provides a synthetic normalized representation of each frame. This representation includes information about player, referee, and ball positions, as well as player and referee velocities, for every labeled game situation. We obtained said details automatically by using an object detector to infer the positions of players, referees, and the ball in each frame. After tracking the detected agent positions across frames, the extracted coordinates underwent normalization through a 'bird's eye' perspective transform, ensuring that the data remained unaffected by variations in camera configurations across different arenas. Finally, a Kalman filter was applied to improve the robustness of player positions and derive their velocities. The labeling process was performed by domain experts employing a custom system designed to annotate game situations, considering the play type and its contextual setting. In conclusion, researchers can utilize this dataset for several purposes: game analysis, automated broadcasting, or game summarization. Furthermore, this dataset can contribute to a broader understanding of the relationship between player dynamics and game situations, shedding light on the level of granularity required for accurately classifying them."
# abstract_short = ""

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Dataset", "Handball Play Classification", "Machine Learning"]

# Links (optional).
url_pdf ="https://www.sciencedirect.com/science/article/pii/S2352340923009101"
#url_preprint = ""
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1016/j.dib.2023.109848"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Example of each game situation and its representation in our normalized space, with positions represented by blue dots, and velocities by orange vectors."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

