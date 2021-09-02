---
title: "Per Garment Capture and Synthesis for Real-time Virtual Try-on"
authors:
- Toby Chong
- I-Chao Shen
- admin
- Takeo Igarashi

date: "2021-10-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 33rd Annual ACM Symposium on User Interface Software and Technology
publication_short: In UIST 2021

abstract: |
  Virtual try-on is a promising application of computer graphics and human computer interaction that can have a profound real-world impact especially during this pandemic. Existing image-based works try to synthesize a try-on image from a single image of a target garment, but it inherently limits the ability to react to possible interactions. It is difficult to reproduce the change of wrinkles caused by pose and body size change, as well as pulling and stretching of the garment by hand.\
  \
  In this paper, we propose an alternative per garment capture and synthesis workflow to handle such rich interactions by training the model with many systematically captured images. Our workflow is composed of two parts: garment capturing and clothed person image synthesis. We designed an actuated mannequin and an efficient capturing process that collects the detailed deformations of the target garments under diverse body sizes and poses.\
  \
  Furthermore, we proposed to use a custom-designed measurement garment, and we captured paired images of the measurement garment and the target garments. We then learn a mapping between the measurement garment and the target garments using deep image-to-image translation. The customer can then try on the target garments interactively during online shopping.



# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cloth Modeling
- Machine Learning
- Interactive Modeling
featured: false

links:
- name: Project Page
  url: https://sites.google.com/view/deepmannequin/home

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "Virtual Try-on"
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


