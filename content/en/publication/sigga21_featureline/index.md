---
title: "Physically-based Feature Line Rendering"
authors:
- rexwest

date: "2021-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Graphics
publication_short: SIGGRAPH Asia 2021

abstract: |
  Feature lines visualize the shape and structure of 3D objects, and are an essential component of many non-photorealistic rendering styles. Existing feature line rendering methods, however, are only able to render feature lines in limited contexts, such as on immediately visible surfaces or in specular reflections. We present a novel, path-based method for feature line rendering that allows for the accurate rendering of feature lines in the presence of complex physical phenomena such as glossy reflection, depth-of-field, and dispersion. Our key insight is that feature lines can be modeled as view-dependent light sources. These light sources can be sampled as a part of ordinary paths, and seamlessly integrate into existing physically-based rendering methods. We illustrate the effectiveness of our method in several real-world rendering scenarios with a variety of different physical phenomena.



# Summary. An optional shortened abstract.
summary: In this paper we present a path-based method for incorporating feature lines into physically-based rendering by modeling them as view-dependent, implicit light sources.

tags:
- Rendering
featured: false

links:
- name: Project Page
  url: http://lines.rexwe.st/

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "feature line"
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


