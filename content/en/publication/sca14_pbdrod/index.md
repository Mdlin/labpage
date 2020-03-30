---
title: "Position-based Elastic Rod"
authors:
- admin
- Ryan Schmidt 
- Jos  Stam

date: "2014-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2014-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM SIGGRAPH/Eurographics Symposium on Computer Animation (SCA 2014)*
publication_short: In *SCA 2014*

abstract: We present a novel method to simulate complex bending and twisting of elastic rods. Elastic rods are commonly simulated using force based methods, such as the finite element method. These methods are accurate, but do not directly fit into the more efficient position-based dynamics framework, since the definition of material frames are not entirely based on positions. We introduce ghost points, which are additional points defined on edges, to naturally endow continuous material frames on discretized rods. We achieve robustness by a novel discretization of the Cosserat theory. The method supports coupling with a frame, a triangle, and a rigid body at the rod’s end point. Our formulation is highly efficient, capable of simulating hundreds of strands in real-time.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Physics Simulation
featured: false

links:
- name: ACM Digital Library
  url: https://dl.acm.org/doi/10.5555/2849517.2849522
- name: YouTube Video
  url: https://www.youtube.com/watch?v=6f3UYHnR4zU
url_video: https://www.dropbox.com/s/jkf5v2e3ncxcsrt/2014_sca_PositionBasedElasticRod.mov?dl=0
url_pdf: https://www.dropbox.com/s/ccq50x7vf63y1q7/2014_sca_PositionBasedElasticRod.pdf?dl=0
url_slides: https://www.dropbox.com/s/1px0smk566m92tg/2017_siggatb_ExploringGenerative3DShapes_Slide.pdf

youtubeid: 6f3UYHnR4zU

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<!--
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
-->