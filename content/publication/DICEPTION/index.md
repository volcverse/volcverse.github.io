---
title: "Diception: A Generalist Diffusion Model for Visual Perceptual Tasks"
authors:
- admin
date: "2025-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Our primary goal here is to create a good, generalist perception model that can tackle multiple tasks, within limits on computational resources and training data. To achieve this, we resort to text-to-image diffusion models pre-trained on billions of images. Our exhaustive evaluation metrics demonstrate that DICEPTION effectively tackles multiple perception tasks, achieving performance on par with state-of-the-art models. We achieve results on par with SAM-vit-h using only 0.06% of their data (e.g., 600K vs. 1B pixel-level annotated images). Inspired by Wang et al., DICEPTION formulates the outputs of various perception tasks using color encoding; and we show that the strategy of assigning random colors to different instances is highly effective in both entity segmentation and semantic segmentation. Unifying various perception tasks as conditional image generation enables us to fully leverage pre-trained text-to-image models. Thus, DICEPTION can be efficiently trained at a cost of orders of magnitude lower, compared to conventional models that were trained from scratch. When adapting our model to other tasks, it only requires fine-tuning on as few as 50 images and 1% of its parameters. DICEPTION provides valuable insights and a more promising solution for visual generalist models.

# Summary. An optional shortened abstract.
summary: One single model solves multiple perceptual tasks, on par with SOTA specialized model.

tags:
- Diffusion Model

featured: true

links:
- name: Homepage
  url: https://aim-uofa.github.io/Diception/
url_pdf: https://arxiv.org/abs/2502.17157
url_code: 'https://github.com/aim-uofa/Diception'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
