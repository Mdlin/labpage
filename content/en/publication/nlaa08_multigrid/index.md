---
title: A Multigrid-Based Shifted-Laplacian Preconditioner for a Fourth-Order Helmholtz Discretization
authors:
- admin
- Scott Maclachlan
- Kees Oosterlee
date: "2009-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2009-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Numerical Linear Algebra with Applications, Volume 16, Issue 8*
publication_short: In *NLAA*

abstract: In this paper, an iterative solution method for a fourth‐order accurate discretization of the Helmholtz equation is presented. The method is a generalization of that presented in (SIAM J. Sci. Comput. 2006; 27:1471–1492), where multigrid was employed as a preconditioner for a Krylov subspace iterative method. The multigrid preconditioner is based on the solution of a second Helmholtz operator with a complex‐valued shift. In particular, we compare preconditioners based on a point‐wise Jacobi smoother with those using an ILU(0) smoother, we compare using the prolongation operator developed by de Zeeuw in (J. Comput. Appl. Math. 1990; 33:1–27) with interpolation operators based on algebraic multigrid principles, and we compare the performance of the Krylov subspace method Bi‐conjugate gradient stabilized with the recently introduced induced dimension reduction method, IDR(s). These three improvements are combined to yield an efficient solver for heterogeneous problems.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Physics Simulation
- Sound Simulation
featured: false

links:
- name: Wiley Online Library
  url: https://doi.org/10.1002/nla.634
url_pdf: https://www.dropbox.com/s/864xkydhahuisul/2009_nla_Helmholtz.pdf?dl=0

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

<!--
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
-->
