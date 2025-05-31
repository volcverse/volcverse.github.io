---
title: "AutoStory: Generating Diverse Storytelling Images with Minimal Human Efforts"
authors:
- Wen Wang
- admin
- Hao Chen
- Zhekai Chen
- Kecheng Zheng
- Chunhua Shen
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IJCV 2024"
publication_short: ""

abstract: Story visualization aims to generate a series of images that match the story described in texts, and it requires the generated images to satisfy high quality, alignment with the text description, and consistency in character identities. Given the complexity of story visualization, existing methods drastically simplify the problem by considering only a few specific characters and scenarios, or requiring the users to provide per-image control conditions such as sketches. However, these simplifications render these methods incompetent for real applications. To this end, we propose an automated story visualization system that can effectively generate diverse, high-quality, and consistent sets of story images, with minimal human interactions. Specifically, we utilize the comprehension and planning capabilities of large language models for layout planning, and then leverage large-scale text-to-image models to generate sophisticated story images based on the layout. We empirically find that sparse control conditions, such as bounding boxes, are suitable for layout planning, while dense control conditions, e.g., sketches, and keypoints, are suitable for generating high-quality image content. To obtain the best of both worlds, we devise a dense condition generation module to transform simple bounding box layouts into sketch or keypoint control conditions for final image generation, which not only improves the image quality but also allows easy and intuitive user interactions. In addition, we propose a simple yet effective method to generate multi-view consistent character images, eliminating the reliance on human labor to collect or draw character images. This allows our method to obtain consistent story visualization even when only texts are provided as input. Both qualitative and quantitative experiments demonstrate the superiority of our method.

# Summary. An optional shortened abstract.
summary: Generating Diverse Storytelling Images with Minimal Human Efforts.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s11263-024-02309-y
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
