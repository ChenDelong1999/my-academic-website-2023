---
title: "Few-shot Classification Guided by Generalization Error Bound"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fan Liu
- Sai Yang
- admin
- Huaxi Huang
- Jun Zhou


author_notes:
- ""
- ""

date: "2023-08-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Pattern Recognition*. [[DOI]](https://www.sciencedirect.com/science/article/pii/S0031320323006027)
publication_short: In *Pattern Recognition* [[DOI]](https://www.sciencedirect.com/science/article/pii/S0031320323006027)

abstract: 'Recently, transfer learning has generated promising performance in few-shot classification by pre-training a backbone network on base classes and then applying it to novel classes. Nevertheless, there lacks a theoretical analysis on how to reduce the generalization error during the learning process. To fill this gap, we prove that the classification error bound on novel classes is mainly determined by the base-class generalization error, given the base-novel domain divergence and the novel-class generalization error produced by an incremental learner using novel samples. The novel-class generalization error is further decided by the base-class empirical error and the VC-dimension of the hypothesis space. Based on this theoretical analysis, we propose a Born-Again Networks under Self-supervised Label Augmentation (BANs-SLA) method to improve the generalization capability of classifiers. In this method, cross-entropy and supervised contrastive losses are simultaneously used to minimize the base-class empirical error in the expanded space with SLA. Afterward, BANs are adopted to transfer the knowledge sequentially across generations, which acts as an effective regularizer to trade-off the VC-dimension. Extensive experimental results have verified the effectiveness of our method, which establishes the new state-of-the-art performance on popular few-shot classification benchmark datasets.'
# Summary. An optional shortened abstract.
summary:  ""

tags: [Computer Vision, Deep Learning]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/pr2023few/few_shot_classification_guided_by_generalization_error_bound.pdf'
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
