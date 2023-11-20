---
title: "Inverse Resource Rational Based Stochastic Driver Behavior Model"
authors:
- Mehmet
- admin
date: "2022-10-02T00:00:00Z"
doi: "https://doi.org/10.1016/j.ifacol.2022.11.186"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2022 IFAC Modeling, Estimation and Control Conference*
publication_short: In *IFAC Modeling, Estimation and Control Conference*

abstract: Human drivers have limited and time-varying cognitive resources when making decisions in real-world traffic scenarios, which often leads to unique and stochastic behaviors that can not be explained by perfect rationality assumption, a widely accepted premise in modeling driving behaviors that presume drivers rationally make decisions to maximize their own rewards under all circumstances. To explicitly address this disadvantage, this study presents a novel driver behavior model that aims to capture the resource rationality and stochasticity of the human driver’s behaviors in realistic longitudinal driving scenarios. The resource rationality principle can provide a theoretic framework to better understand the human cognition processes by modeling human’s internal cognitive mechanisms as utility maximization subject to cognitive resource limitations, which can be represented as finite and time-varying preview horizons in the context of driving. An inverse resource rational-based stochastic inverse reinforcement learning approach (IRR-SIRL) is proposed to learn a distribution of the planning horizon and cost function of the human driver with a given series of human demonstrations. A nonlinear model predictive control (NMPC) with a time-varying horizon approach is used to generate driver-specific trajectories by using the learned distributions of the planning horizon and the cost function of the driver. The simulation experiments are carried out using human demonstrations gathered from the driver-in-the-loop driving simulator. The results reveal that the proposed inverse resource rational-based stochastic driver model can address the resource rationality and stochasticity of human driving behaviors in a variety of realistic longitudinal driving scenarios.

# Summary. An optional shortened abstract.
summary:

tags:
- Conference
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2207.07088
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
