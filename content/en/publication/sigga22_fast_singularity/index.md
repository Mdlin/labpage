---
title: "Fast Editing of Singularities in Field-Aligned Stripe Patterns"
authors:
- Yuta Noma
- admin
- Yoshihiro Kawahara

date: "2022-10-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of SIGGRAPH Asia 2022
publication_short: SIGGRAPH Asia 2022

abstract:
  "Field-aligned parametrization is a method that maps a scalar function onto a surface, such that the gradient vector of the scalar function matches the input vector field. Using this idea, one can produce a stripe pattern that is convenient for various purposes such as remeshing, texture synthesis, and computational fabrication. In the final outcome, the positions of singularities (i.e., bifurcations of the stripe pattern) are essential for functionalities, manufacturability, or aesthetics. In this paper, we propose an algorithm to allow users to interactively edit the singularity positions of field-aligned stripe patterns. The algorithm computes a stripe pattern from a prescribed set of singularities, without generating any unwanted singularities. The solution of the algorithm is formulated as the global minima of a constrained quadratic optimization, whose computation speed is dominated by solving only two sparse linear systems. Furthermore, once the two matrices in the two linear systems are factorized, any update on singularity positions operates in linear time. We showcase several applications feasible with our fast yet simple algorithm."



# Summary. An optional shortened abstract.
summary: In this paper, we propose an algorithm to allow users to interactively edit the singularity positions of field-aligned stripe patterns.

tags:
- Computational Fabrication
- Geometry Processing
- Interactive Modeling
featured: false

links:
- name: Project Page
  url: https://yutanoma.com/projects/singularity-editing

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


