---
title: "Learning Three-dimensional Flow for Interactive Aerodynamic Design"
authors:
- admin
- Bernd Bickel
date: "2018-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transation of Graphics (SIGGRAPH 2018)*
publication_short: In *SIGGRAPH 2018*

abstract: We present a data-driven technique to instantly predict how fluid flows around various three-dimensional objects. Such simulation is useful for computational fabrication and engineering, but is usually computationally expensive since it requires solving the Navier-Stokes equation for many time steps. To accelerate the process, we propose a machine learning framework which predicts aerodynamic forces and velocity and pressure fields given a three-dimensional shape input. Handling detailed free-form three-dimensional shapes in a data-driven framework is challenging because machine learning approaches usually require a consistent parametrization of input and output. We present a novel PolyCube maps-based parametrization that can be computed for three-dimensional shapes at interactive rates. This allows us to efficiently learn the nonlinear response of the flow using a Gaussian process regression. We demonstrate the effectiveness of our approach for the interactive design and optimization of a car body.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Machine Learning
- Geometry Processing
- Physics Simulation
- Fluid Dynamics
- Interactive Modeling
featured: false

links:
- name: ACM Digital Library
  url: https://dl.acm.org/doi/10.1145/3197517.3201325
- name: YouTube Video
  url: https://www.youtube.com/watch?v=U38cKk-sxyY
url_pdf: https://www.dropbox.com/s/ndyk2lvdv6f3741/2018_sigg_Learning3DAerodynamics.pdf
url_slides: https://www.dropbox.com/s/endkt45yfoxj0fq/2018_sigg_mlcfd_slides.pdf

youtubeid: U38cKk-sxyY


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

