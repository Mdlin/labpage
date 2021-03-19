---
title: "Real-Time Example-Based Elastic Deformation"
authors:
- Yuki Koyama
- Kenshi Takayama
- admin
- Takeo Igarashi

date: "2012-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2012-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM SIGGRAPH/Eurographics Symposium on Computer Animation (SCA 2012)*
publication_short: In *SCA 2012*

abstract: We present an example-based elastic deformation method that runs in real time. Example-based elastic deformation was originally presented by Martin et al. [MTGG11], where an artist can intuitively control elastic material behaviors by simply giving example poses. Their FEM-based approach is, however, computationally expensive requiring nonlinear optimization, which hinders its use in real-time applications such as games. Our contribution is to formulate an analogous concept using the shape matching framework, which is fast, robust, and easy to implement. The key observation is that each overlapping local region's right stretch tensor obtained by polar decomposition is a natural choice for a deformation descriptor. This descriptor allows us to represent the pose space as a linear blending of examples. At each time step, the current deformation descriptor is linearly projected onto the example manifold, and then used to modify the rest shape of each local region when computing goal positions. Our approach is two orders of magnitude faster than Martin et al.'s approach while producing comparable example-based elastic deformations.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Physics Simulation
featured: false

links:
- name: ACM Digital Library
  url: https://dl.acm.org/doi/10.1145/3145749.3145758
- name: YouTube Video
  url: https://www.youtube.com/watch?v=45QjojWiOEc
- name: Project Page
  url: https://koyama.xyz/project/ExampleBasedShapeMatching/index.html

youtubeid: 45QjojWiOEc

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

