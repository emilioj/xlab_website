---
title: 'Immersive 3D Medical Visualization in Virtual Reality using Stereoscopic Volumetric Path Tracing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - taibo
  - jalley

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-03'
doi: '10.1109/VR58804.2024.00123'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE Conference Virtual Reality and 3D User Interfaces (VR)*
publication_short: In *IEEEVR'24*

abstract: Scientific visualizations using physically-based lighting models play a crucial role in enhancing both image quality and realism. In the domain of medical visualization, this trend has gained significant traction under the term cinematic rendering (CR). It enables the creation of 3D photorealistic reconstructions from medical data, offering great potential for aiding healthcare professionals in the analysis and study of volumetric datasets. However, the adoption of such advanced rendering for immersive virtual reality (VR) faces two main limitations related to their high computational demands. First, these techniques are frequently used to produce pre-recorded videos and offline content, thereby restricting interactivity to predefined volume appearance and lighting settings. Second, when deployed in head-tracked VR environments they can induce cybersickness symptoms due to the disturbing flicker caused by noisy Monte Carlo renderings. Consequently, the scope for meaningful interactive operations is constrained in this modality, in contrast with the versatile capabilities of classical direct volume rendering (DVR). In this work, we introduce an immersive 3D medical visualization system capable of producing photorealistic and fully interactive stereoscopic visualizations on head-mounted display (HMD) devices. Our approach extends previous linear regression denoising to enable real-time stereoscopic cinematic rendering within AR/VR settings. We demonstrate the capabilities of the resulting VR system, like its interactive rendering, appearance and transfer function editing.

# Summary. An optional shortened abstract.
summary: This paper presented an immersive 3D medical visualization system enabling VPT for stereoscopic virtual reality. Our approach combined stereoscopic rendering with state-of-the-art image reprojection and denoising techniques to meet the requirements of VR experiences. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Video 1
  url: https://youtu.be/9GHqwhqN_KQ
- name: Video 2
  url: https://youtu.be/Ida-fWn_clA

url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
url_project: ''
url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtu.be/9GHqwhqN_KQ'
#url_video: 'https://youtu.be/Ida-fWn_clA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Stereoscopic interactive session rendering a photorealistic 3D reconstruction of the HAND CT scan.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

## Video (Interactive Live-Sessions)

{{< youtube 9GHqwhqN_KQ >}}

## Video (Temporal Flicker Comparisons)

{{< youtube Ida-fWn_clA >}}

## Copyright Disclaimer

This is the author's version of the work. It is posted here for your personal use. Not for redistribution.  
© 2024 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component of this work in other works.

## Related Work

## Acknowledgments

The anonymized medical datasets employed in this study were obtained courtesy of the OsiriX Foundation (specifically, MANIX and MACOESSIX), and were freely available through Embodi3D LLC (HAND). We thank Prof. Jérôme Schmid for the helpful and insightful discussions about the usability of the system by healthcare professionals. We also thank Prof. Bochang Moon for our helpful discussions on image-based denoising using weighted recursive least squares. Both authors would like to express their gratitude with Tom Boudard, Enrique García, Cristina Pelayo and Miguel Osorio who all helped us improve the VR GUI and tools of the system. We also thank Manuel Silva for his last-minute help in preparing the supplementary website, and Bea Blanco for her administrative assistance. We also thank Giovanni Fiorilli for his support in building our HTC Developer Partnership. Jose A. Iglesias-Guitian was supported by a 2021 Leonardo Grant for Researchers and Cultural Creators, BBVA Foundation. He also acknowledges the UDC-Inditex InTalent programme, the Spanish Ministry of Science and Innovation (AEI/RYC2018-025385-I) and Xunta de Galicia (ED431F 2021/11).
