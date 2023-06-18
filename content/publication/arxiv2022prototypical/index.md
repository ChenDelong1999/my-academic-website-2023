---
title: "ProtoCLIP: Prototypical Contrastive Language Image Pretraining"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zhao Wu
- Fan Liu
- Zaiquan Yang
- Shaoqiu Zheng
- Ying Tan
- Erjin Zhou

# Author notes (optional)
# author_notes:

date: "2022-06-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ArXiv Technical Report. [[ArXiv]](https://arxiv.org/abs/2206.10996)
publication_short: ArXiv Technical Report. [[ArXiv]](https://arxiv.org/abs/2206.10996)

abstract: 'Contrastive Language Image Pretraining (CLIP) received widespread attention since its learned representations can be transferred well to various downstream tasks. During CLIP training, the InfoNCE objective aims to align positive image-text pairs and separate negative ones. In this paper, we show a representation grouping effect during this process: the InfoNCE objective indirectly groups semantically similar representations together via randomly emerged within-modal anchors. We introduce Prototypical Contrastive Language Image Pretraining (ProtoCLIP) to enhance such grouping by boosting its efficiency and increasing its robustness against modality gap. Specifically, ProtoCLIP sets up prototype-level discrimination between image and text spaces, which efficiently transfers higher-level structural knowledge. We further propose Prototypical Back Translation (PBT) to decouple representation grouping from representation alignment, resulting in effective learning of meaningful representations under large modality gap. PBT also enables us to introduce additional external teachers with richer prior knowledge. ProtoCLIP is trained with an online episodic training strategy, which makes it can be scaled up to unlimited amounts of data. We train our ProtoCLIP on Conceptual Captions and achieved an +5.81% ImageNet linear probing improvement and an +2.01% ImageNet zero-shot classification improvement. On larger YFCC dataset, ProtoCLIP matches the performance of CLIP with 4×fewer pretraining epochs.'

# Summary. An optional shortened abstract.
summary: "> <font color='gray' size=3>*This paper proposed ProtoCLIP for improved representation grouping and enhanced robustness against modality gap in large-scale vision language pretraining. ProtoCLIP improved linear probing and zero-shot accuracy by 5.8% and 2.0%, and matched the performance of CLIP with 4×fewer epochs.*</font>


**<u>Delong Chen</u>**, Zhao Wu, [Fan Liu](https://multimodality.group/author/%E5%88%98%E5%87%A1/), Zaiquan Yang, [Shaoqiu Zheng](https://scholar.google.com/citations?user=SzXZH6kAAAAJ), [Ying Tan](https://scholar.google.com/citations?user=PjNxSPsAAAAJ), [Erjin Zhou](https://scholar.google.com/citations?user=k2ziPUsAAAAJ). [*ArXiv preprint*](https://arxiv.org/abs/2206.10996), 2022 (under review)"
tags: [Deep Learning, Multimodal Learning, Computer Vision, Self-supervised Learning]
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/arxiv2022prototypical/prototypical_contrastive_language_image_pretraining.pdf'
url_code: 'https://github.com/megvii-research/protoclip'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

