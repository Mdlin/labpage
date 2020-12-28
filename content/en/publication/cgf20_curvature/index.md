---
title: "A Curvature and Density‐based Generative Representation of Shapes"
authors:
- Zi Ye
- admin
- Takeo Igarashi
- Tim Hoffmann
date: "2020-9-5T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computer Graphics Forum 2020
publication_short: In CGF 2020

abstract: This paper introduces a generative model for 3D surfaces based on a representation of shapes with mean curvature and metric, which are invariant under rigid transformation. Hence, compared with existing 3D machine learning frameworks, our model substantially reduces the influence of translation and rotation. In addition, the local structure of shapes will be more precisely captured, since the curvature is explicitly encoded in our model. Specifically, every surface is first conformally mapped to a canonical domain, such as a unit disk or a unit sphere. Then, it is represented by two functions":" the mean curvature half‐density and the vertex density, over this canonical domain. Assuming that input shapes follow a certain distribution in a latent space, we use the variational autoencoder to learn the latent space representation. After the learning, we can generate variations of shapes by randomly sampling the distribution in the latent space. Surfaces with triangular meshes can be reconstructed from the generated data by applying isotropic remeshing and spin transformation, which is given by Dirac equation. We demonstrate the effectiveness of our model on datasets of man‐made and biological shapes and compare the results with other methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Machine Learning
- Geometry Processing
featured: false

links:
- name: Wiley Online Library
  url: https://doi.org/10.1111/cgf.14094

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


