---
title: "Neural Sequence Transformation"
authors:
- smukherjee2016
- Sayan Mukherjee
- Son Hua
- admin
- meistdan

date: "2021-11-15T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: true

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum (Proceedings of Pacific Graphics 2021)*
publication_short: In *PG 2021*

abstract: Monte Carlo integration is a technique for numerically estimating a definite integral by stochastically sampling its integrand. These samples can be averaged to make an improved estimate, and the progressive estimates form a sequence that converges to the integral value on the limit. Unfortunately, the sequence of Monte Carlo estimates converges at a rate of O(√n), where n denotes the sample count, effectively slowing down as more samples are drawn. To overcome this, we can apply sequence transformation, which transforms one converging sequence into another with the goal of accelerating the rate of convergence. However, analytically finding such a transformation for Monte Carlo estimates can be challenging, due to both the stochastic nature of the sequence, and the complexity of the integrand. In this paper, we propose to leverage neural networks to learn sequence transformations that improve the convergence of the progressive estimates of Monte Carlo integration. We demonstrate the effectiveness of our method on several canonical 1D integration problems as well as applications in light transport simulation.

# Summary. An optional shortened abstract.
summary: A data-driven approach to applying sequence transformation to Monte Carlo integration.

tags:
- Rendering
featured: false

links:
- name: Project Page
  url: https://smukherjee2016.github.io/publication/neural-sequence-transformation



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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
