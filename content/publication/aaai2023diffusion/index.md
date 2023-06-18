---
title: "Taming Diffusion Models for Music-driven Conducting Motion Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhuoran Zhao
- Jinbin Bai
- admin
- Debang Wang
- Yubo Pan


author_notes:
- ""
- "Joint First Author"

date: "2023-05-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[AAAI 2023 Inaugural Summer Symposium Series](https://aaai.org/conference/summer-symposia/summer-series-2023/) - [AI x Metaverse](https://sites.google.com/view/aaai23-ai-x-metaverse/home)"
publication_short: AAAI 2023 Inaugural Summer Symposium Series - AI x Metaverse

abstract: 'Generating the motion of orchestral conductors from a given piece of symphony music is a challenging task since it requires a model to learn semantic music features and capture the underlying distribution of real conducting motion. Prior works have applied Generative Adversarial Networks (GAN) to this task, but the promising diffusion model, which recently showed its advantages in terms of both training stability and output quality, has not been exploited in this context. This paper presents Diffusion-Conductor , a novel DDIM-based approach for music-driven conducting motion generation, which integrates the diffusion model to a two-stage learning framework. We further propose a random masking strategy to improve the feature robustness, and use a pair of geometric loss functions to impose additional regularizations and increase motion diversity. We also design several novel metrics, including Frechet Gesture Distance (FGD) and Beat Consistency Score (BC) for a more comprehensive evaluation of the generated motion. Experimental results demonstrate the advantages of our model.'

# Summary. An optional shortened abstract.
summary: 'We present a comprehensive survey on Single Sample Per Person (SSPP) Face Recognition. [[DOI]](https://doi.org/10.1007/s10462-022-10240-2)'
tags: [Music Information Retrieval, Multimodal Learning]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/aaai2023diffusion/AAAI_2023_Symposium_Taming.pdf'
url_code: 'https://github.com/viiika/Diffusion-Conductor'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

