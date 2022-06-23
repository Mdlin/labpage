---
title: "Neural Motion Compression with Frequency-adaptive Fourier Feature Network"
authors:
- kenji-tojo
- yifei
- admin
date: "2022-03-01T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: false

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Eurographics 2022 Short Paper Program (EG 2022 short)*
publication_short: In *EG 2022 short*

abstract: We present a neural-network-based compression method to alleviate the storage cost of motion capture data. Human motions such as locomotion, often consist of periodic movements. We leverage this periodicity by applying Fourier features to a multilayered perceptron network. Our novel algorithm finds a set of Fourier feature frequencies based on the discrete cosine transformation (DCT) of motion. During training, we incrementally added a dominant frequency of the DCT to a current set of Fourier feature frequencies until a given quality threshold was satisfied. We conducted an experiment using CMU motion dataset, and the results suggest that our method achieves overall high compression ratios while maintaining its quality.

# Summary. An optional shortened abstract.
summary: We present a neural-network-based compression method to alleviate the storage cost of motion capture data. We leverage this periodicity by applying Fourier features to a multilayered perceptron network. 

tags:
- Data-driven Animation
- Machine Learning
- Character Animation
featured: false

links:
- name: Slide
  url: https://docs.google.com/presentation/d/1oWtMtblYendjuD3_kiNAcIK7SnRXs0bl/edit?usp=sharing&ouid=114828650557921591095&rtpof=true&sd=true
- name: Supplemental Video
  url: https://www.youtube.com/watch?v=6IybU9WHGaI   
- name: Presentation Video
  url: https://www.youtube.com/watch?v=EHqazKBkNt4
url_pdf: https://www.dropbox.com/s/z4rnklja92jnpzh/2022_egshort_neuralcompression.pdf?dl=0


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

