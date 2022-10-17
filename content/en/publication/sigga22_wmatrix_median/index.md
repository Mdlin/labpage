---
title: "Constant Time Median Filter using 2D Wavelet Matrix"
authors:
- moroto
- admin

date: "2022-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Graphics (SIGGRAPH Asia 2022)
publication_short: SIGGRAPH Asia 2022

abstract:
  "The median filter is a simple yet powerful noise reduction technique that is extensively applied in image, signal, and speech processing. It can effectively remove impulsive noise while preserving the content of the image by taking the median of neighboring pixels; thus, it has various applications, such as restoration of a damaged image and facial beautification. The median filter is typically implemented in one of two major approaches: the histogram-based method, which requires O(1) computation time per pixel when focusing on the kernel radius r, and the sorting-based method, which requires approximately O(r^2) computation time per pixel but has a light constant factor. These are used differently depending on the kernel radius and the number of bits in the image. However, the computation time is still slow, particularly when the kernel radius is in the mid to large range. This paper introduces novel and efficient median filter with constant complexity O(1) for kernel size using the wavelet matrix data structure, which has been applied to query-based searches on one-dimensional data. We extended the original wavelet matrix to two-dimensional data for application to computer graphics problems. The objective of this study was to achieve high-speed median filter computation in parallel computing environment with many threads (i.e., GPUs). Our implementation for the GPU is an order of magnitude faster than the histogram method for 8-bit images. Unlike traditional histogram methods, which suffer from significant computational overhead, the proposed method can handle images with high pixel depth (e.g., 16- and 32-bit high dynamic range images). When the kernel radius is greater than 12 for 8-bit images, the proposed method outperforms the other median filter computation methods."



# Summary. An optional shortened abstract.
summary: In this paper, we have implemented a completely new constant-time median filter based on Wavelet Matrix, which can be efficiently executed by a GPU and supports HDR images.

tags:
- Image Processing
featured: false

links:
url_pdf: https://www.dropbox.com/s/8f9k88xqn4ecgv1/2022_sigga_wavelet.pdf

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



### Supplementary Materials Code
We are currently preparing an implementation of a median filter using wavelet matrix for release on GitHub.
Until the GitHub repository is ready for publication, we are publishing the supplementary materials code for the paper submission.
This code is based on [the Supplemental Material Code for "Fast median filters using separable sorting networks"](https://dl.acm.org/doi/10.1145/3450626.3459773) [Adams 2021], with the addition of our methods.
This supplementary materials includes code for CPUs, where readability is more important than speed, and code for CUDAs, where speed is the highest priority.
- [Download here (Google Drive)](https://drive.google.com/file/d/1Jr2mQlixt_tN-vo2gfvgMCRx46nVgNsF/view?usp=sharing)

The GitHub version, to be released in November, will include the following updates
- Improved readability
- Support for multiple channels
- Reduced memory usage by about 40~50%.
