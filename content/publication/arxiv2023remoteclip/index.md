---
title: "RemoteCLIP: A Vision Language Foundation Model for Remote Sensing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fan Liu
- admin
- Qingyun Guanzhang
- Xiaocong Zhou
- Jiale Zhu
- Jun Zhou


author_notes:
- ""
- "Joint First Author"

date: "2023-06-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ArXiv Preprint
publication_short: ArXiv Preprint

abstract: 'General-purpose foundation models have become increasingly important in the field of artificial intelligence. While self-supervised learning (SSL) and Masked Image Modeling (MIM) have led to promising results in building such foundation models for remote sensing, these models primarily learn low-level features, require annotated data for fine-tuning, and not applicable for retrieval and zero-shot applications due to the lack of language understanding. In response to these limitations, we propose RemoteCLIP, the first vision-language foundation model for remote sensing that aims to learn robust visual features with rich semantics, as well as aligned text embeddings for seamless downstream application. To address the scarcity of pre-training data, we leverage data scaling, converting heterogeneous annotations based on Box-to-Caption (B2C) and Mask-to-Box (M2B) conversion, and further incorporating UAV imagery, resulting a 12xlarger pretraining dataset. RemoteCLIP can be applied to a variety of downstream tasks, including zero-shot image classification, linear probing, k-NN classification, few-shot classification, image-text retrieval, and object counting. Evaluations on 16 datasets, including a newly introduced RemoteCount benchmark to test the object counting ability, show that RemoteCLIP consistently outperforms baseline foundation models across different model scales. Impressively, RemoteCLIP outperform previous SoTA by 9.14% mean recall on RSICD dataset and by 8.92% on RSICD dataset. For zero-shot classification, our RemoteCLIP outperform CLIP baseline by up to 6.39% average accuracy on 12 downstream datasets.'
# Summary. An optional shortened abstract.
summary:  "> <font color='gray' size=3> *We introduced RemoteCLIP, the first general-purpose vision-language foundation model for remote sensing. RemoteCLIP outperform previous image-text retrieval SoTA by 9.14% mean recall on RSICD dataset and by 8.92% on RSICD dataset. For zero-shot classification, our RemoteCLIP outperform CLIP baseline by up to 6.39% average accuracy on 12 downstream datasets.*</font>


[Fan Liu](https://multimodality.group/author/%E5%88%98%E5%87%A1/), **<u>Delong Chen</u>** (joint first author), Qingyun Guanzhang, Xiaocong Zhou, Jiale Zhu, [Jun Zhou](https://experts.griffith.edu.au/7205-jun-zhou). *Arxiv Preprint* 2023.
"

tags: [Multimodal Learning, Computer Vision, Deep Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/arxiv2023remoteclip/remoteclip.pdf'
url_code: ''
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

