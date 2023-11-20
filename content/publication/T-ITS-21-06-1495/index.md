---
title: "Distributed Stochastic Model Predictive Control for Human-Leading Heavy-Duty Truck Platoon"
authors:
- Mehmet
- admin
date: "2022-02-24T00:00:00Z"
doi: "10.1109/TITS.2022.3147719"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Intelligent Transportation Systems"
publication_short: ""

abstract: Human-leading truck platooning systems have been proposed to leverage the benefits of both human supervision and vehicle autonomy. Equipped with human guidance and autonomous technology, human-leading truck platooning systems are more versatile to handle uncertain traffic conditions than fully automated platooning systems. This paper presents a novel distributed stochastic model predictive control (DSMPC) design for a human-leading heavy-duty truck platoon. The proposed DSMPC design integrates the stochastic driver behavior model of the human-driven leader truck with a distributed formation control design for the following automated trucks in the platoon. The driver behavior of the human-driven leader truck is learned by a stochastic inverse reinforcement learning (SIRL) approach. The proposed stochastic driver behavior model aims to learn a distribution of cost function, which represents the richness and uniqueness of human driver behaviors, with a given set of driver-specific demonstrations. The distributed formation control includes a serial DSMPC with guaranteed recursive feasibility, closed-loop chance constraint satisfaction, and string stability. Simulation studies are conducted to investigate the efficacy of the proposed design under several realistic traffic scenarios. Compared to the baseline platoon control strategy (deterministic distributed model predictive control), the proposed DSMPC achieves superior controller performance in constraint violations and spacing errors.

# Summary. An optional shortened abstract.
summary:

tags:
- Journal
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2201.11859
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
