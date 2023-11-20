---
title: "Eco-Driving of Connected and Automated Vehicle with Preceding Driver Behavior Prediction"
authors:
- Mehmet
- admin
date: "2021-01-01T00:00:00Z"
doi: "https://doi.org/10.1115/1.4048108"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ASME Journal of Dynamic Systems, Measurement and Control"
publication_short: ""

abstract: The development of vehicle connectivity and autonomy in ground transportation is not only able to enhance traffic safety and driving comfort as well as fuel economy. This study presents a receding-horizon optimization-based control strategy integrated with the preceding vehicle speed prediction model to achieve an eco-driving strategy for connected and automated vehicles (CAVs). In the real traffic where the CAV follows a preceding vehicle on the road, a gated recurrent unit (GRU) network is used to predict the behavior of the preceding vehicle by utilizing the historical inter-vehicle information collected through onboard sensors. Then, a nonlinear model predictive control (NMPC) algorithm is adopted for CAV to minimize the accumulated fuel consumption within the preview horizon. The NMPC approach solves the fuel-optimal speed profile of the CAV, considering a predicted short-term speed preview of the preceding vehicle. With the awareness of the preview speed conditions, the fuel consumption of the CAV is reduced by avoiding unnecessary braking and acceleration, especially during transient traffic conditions. The Pareto front framework is used to examine a trade-off between the vehicle speed prediction accuracy, computational burden, and the fuel consumption of the CAV in the proposed GRU-NMPC design. To analyze the effectiveness of the GRU-NMPC design, adaptive cruise control with constant time headway policy (ACC-CTH) is adopted as a benchmark control design. Comparison results show significant fuel economy improvement of the proposed design and expose possible fuel benefits from vehicle autonomy and sensor fusion technology.

# Summary. An optional shortened abstract.
summary:

tags:
- Journal
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
