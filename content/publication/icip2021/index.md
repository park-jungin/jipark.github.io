---
title: 'Self-Balanced Learning for Domain Generalization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jin Kim
  - Jiyoung Lee
  - admin
  - Dongbo Min
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-04-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing*
publication_short: In *ICIP 2021*

abstract: Domain generalization aims to learn a prediction model on multi-domain source data such that the model can generalize to a target domain with unknown statistics. Most existing approaches have been developed under the assumption that the source data is well-balanced in terms of both domain and class. However, real-world training data collected with different composition biases often exhibits severe distribution gaps for domain and class, leading to substantial performance degradation. In this paper, we propose a self-balanced domain generalization framework that adaptively learns the weights of losses to alleviate the bias caused by different distributions of the multi-domain source data. The self-balanced scheme is based on an auxiliary reweighting network that iteratively updates the weight of loss conditioned on the domain and class information by leveraging balanced meta data. Experimental results demonstrate the effectiveness of our method overwhelming state-of-the-art works for domain generalization.

# Summary. An optional shortened abstract.
summary: IEEE International Conference on Image Processing (ICIP) 2021

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9506516'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
