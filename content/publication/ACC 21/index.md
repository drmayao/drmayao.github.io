---
title: "Personalized Adaptive Cruise Control and Impacts on Mixed Traffic"
authors:
- Mehmet
- admin
date: "2021-05-30T00:00:00Z"
doi: "10.23919/ACC50511.2021.9482812"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2021 American Control Conference*
publication_short: In *American Control Conference*

abstract: This paper presents a personalized adaptive cruise control (PACC) design that can learn human driver behavior and adaptively control the semi-autonomous vehicle (SAV) in the car-following scenario, and investigates its impacts on mixed traffic. In mixed traffic where the SAV and human-driven vehicles share the road, the SAV’s driver can choose a PACC tuning that better fits the driver’s preferred driving strategies. The individual driver’s preferences are learned through the inverse reinforcement learning (IRL) approach by recovering a unique cost function from the driver’s demonstrated driving data that best explains the observed driving style. The proposed PACC design plans the motion of the SAV by minimizing the learned unique cost function considering the short preview information of the preceding human-driven vehicle. The results reveal that the learned driver model can identify and replicate the personalized driving behaviors accurately and consistently when following the preceding vehicle in a variety of traffic conditions. Furthermore, we investigated the impacts of the PACC with different drivers on mixed traffic by considering time headway, gap distance, and fuel economy assessments. A statistical investigation shows that the impacts of the PACC on mixed traffic vary among tested drivers due to their intrinsic driving preferences.

# Summary. An optional shortened abstract.
summary:

tags:
- Conference
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/ftp/arxiv/papers/2103/2103.14705.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
