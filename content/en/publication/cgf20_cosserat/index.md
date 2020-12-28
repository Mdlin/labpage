---
title: "A Curvature and Density‐based Generative Representation of Shapes"
authors:
- Jiahao Wen  
- Jiong Chen 
- admin
- Hujun Bao  
- Jin Huang

date: "2020-11-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computer Graphics Forum 2020
publication_short: In CGF 2020

abstract: Rod‐like one‐dimensional elastic objects often exhibit complex behaviors which pose great challenges to the discretization method for pursuing a faithful simulation. By only moving a small portion of material points, the Eulerian‐on‐Lagrangian (EoL) method already shows great adaptivity to handle sharp contact, but it is still far from enough to reproduce rich and complex geometry details arising in simulations. In this paper, we extend the discrete configuration space by unifying all Lagrangian and EoL nodes in representation for even more adaptivity with every sample being assigned with a dynamic material coordinate. However, this great extension will immediately bring in much more redundancy in the dynamic system. Therefore, we propose additional energy to control the spatial distribution of all material points, seeking to equally space them with respect to a curvature‐based density field as a monitor. This flexible approach can effectively constrain the motion of material points to resolve numerical degeneracy, while simultaneously enables them to notably slide inside the parametric domain to account for the shape parameterization. Besides, to accurately respond to sharp contact, our method can also insert or remove nodes online and adjust the energy stiffness to suppress possible jittering artifacts that could be excited in a stiff system. As a result of this hybrid rh‐adaption, our proposed method is capable of reproducing many realistic rod dynamics, such as excessive bending, twisting and knotting while only using a limited number of elements.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Physics Simulation
featured: false

links:
- name: Wiley Online Library
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14133

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: ''
#  focal_point: ""
#  preview_only: false

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


