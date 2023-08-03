---
title: "Few-shot Classification via Ensemble Learning with Multi-Order Statistics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sai Yang
- Fan Liu
- admin
- Jun Zhou


# author_notes:
# - ""
# - "Joint First Author"

date: "2023-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In _IJCAI-23_ (oral) [[arxiv](https://arxiv.org/abs/2305.00454)]
publication_short: In _IJCAI-23_ (oral) [[arxiv](https://arxiv.org/abs/2305.00454)]

abstract: 'Transfer learning has been widely adopted for few-shot classification. Recent studies reveal that obtaining good generalization representation of images on novel classes is the key to improving the few-shot classification accuracy. To address this need, we prove theoretically that leveraging ensemble learning on the base classes can correspondingly reduce the true error in the novel classes. Following this principle, a novel method named Ensemble Learning with Multi-Order Statistics (ELMOS) is proposed in this paper. In this method, after the backbone network, we use multiple branches to create the individual learners in the ensemble learning, with the goal to reduce the storage cost. We then introduce different order statistics pooling in each branch to increase the diversity of the individual learners. The learners are optimized with supervised losses during the pre-training phase. After pre-training, features from different branches are concatenated for classifier evaluation. Extensive experiments demonstrate that each branch can complement the others and our method can produce a state-of-the-art performance on multiple few-shot classification benchmark datasets.'

# Summary. An optional shortened abstract.
summary:  We prove theoretically that leveraging ensemble learning on the base classes can correspondingly reduce the true error in the novel classes. Following this principle, a novel method named Ensemble Learning with Multi-Order Statistics (ELMOS) is proposed in this paper.

tags: [Computer Vision, Deep Learning, Few-shot Learning]

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/ijcai2023few/Few-shot Classification via Ensemble Learning with Multi-Order Statistics.pdf'
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
#   E.g. `internal-project` references `content/project/intesrnal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:

---


