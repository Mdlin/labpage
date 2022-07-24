---
title: "Recolorable Posterization of Volumetric Radiance Fields - Supplemental Video"
authors:
- kenji-tojo
- admin
date: "2022-06-23T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: true

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Eurographics Symposium on Rendering 2022*
publication_short: In *EGSR 2022*

abstract: Volumetric radiance fields have recently gained significant attention as a promising representation for photorealistic scene reconstruction. However, non-photorealistic rendering of such representation has been barely explored. In this study, we investigate artistic posterization of volumetric radiance fields. We extend the recent palette-based image editing framework, which naturally introduces intuitive color manipulation of the posterized results, into the radiance field. Our major challenge is how to apply the stylization effects coherently across different views. Based on the observation that computing a palette frame-by-frame can produce flickering, we propose to pre-compute a single palette from the volumetric radiance field covering its whole visible colors. We present a method based on volumetric visibility to sample visible colors from the radiance field while avoiding occluded and noisy regions. We demonstrate our workflow via application to pre-trained volumetric radiance fields with various stylization effects. We also show that our approach can produce more coherent and robust stylization effects compared to baseline methods computing palette on image.

# Summary. An optional shortened abstract.
summary: We investigate artistic posterization of volumetric radiance fields.

tags:
- Image Processing
- Rendering
- Non-Photorealistic 
featured: false

links:
- name: Project Page
  url: https://kenji-tojo.github.io/publications/posternerf/



youtubeid: xO4uyGcwjXA

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

