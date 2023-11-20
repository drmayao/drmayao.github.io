---
title: "Fuel-Economical Distributed Model Predictive Control for Heavy-Duty Truck Platoon"
authors:
- Mehmet
- admin
date: "2021-09-19T00:00:00Z"
doi: "10.1109/ITSC48978.2021.9565018"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 24th IEEE Intelligent Transportation Systems Conference*
publication_short: In *IEEE Intelligent Transportation Systems Conference*

abstract: This paper proposes a fuel-economical distributed model predictive control design (Eco-DMPC) for a homogenous heavy-duty truck platoon. The proposed control strategy integrates a fuel-optimal control strategy for the leader truck with a distributed formation control for the following trucks in the heavy-duty truck platoon. The fuel-optimal control strategy is implemented by a nonlinear model predictive control (NMPC) design with an instantaneous fuel consumption model. The proposed fuel-optimal control strategy utilizes the preview information of the preceding traffic to achieve the fuel-economical speed planning by avoiding energy-inefficient maneuvers, particularly under transient traffic conditions. The distributed formation control is designed with a serial distributed model predictive control (DMPC) strategy with guaranteed local and string stability. In the DMPC strategy, each following truck acquires the future predicted state information of its predecessor through vehicle connectivity and then applies local optimal control to maintain constant spacing. Simulation studies are conducted to investigate the fuel economy performance of the proposed control strategy and to validate the local and string stability of the platoon under a realistic traffic scenario. Compared with a human-operated platoon and a benchmark formation-controlled platoon, the proposed Eco-DMPC significantly improves the fuel economy and road utilization.

# Summary. An optional shortened abstract.
summary:

tags:
- Conference
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2106.08325.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=-AlxOWy3fwI

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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
