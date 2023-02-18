---
title: 'Graph Regularization Network with Semantic Affinity for Weakly-supervised Temporal Action Localization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jiyoung Lee
  - Sangryul Jeon
  - Seungryong Kim
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2019-04-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-09-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing*
publication_short: In *ICIP 2019*

abstract: This paper presents a novel deep architecture for weakly-supervised temporal action localization that not only generates segment-level action responses but also propagates segment-level responses to the neighborhood in a form of graph Laplacian regularization. Specifically, our approach consists of two sub-modules; a class activation module to estimate the action score map over time through the action classifiers, and a graph regularization module to refine the estimated action score map by solving a quadratic programming problem with the predicted segment-level semantic affinities. Since these two modules are integrated with fully differentiable layers, the proposed networks can be jointly trained in an end-to-end manner. Experimental results on Thumos14 and ActivityNet1.2 demonstrate that the proposed method provides outstanding performances in weakly-supervised temporal action localization.

# Summary. An optional shortened abstract.
summary: IEEE International Conference on Image Processing (ICIP) 2019

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/8803589'
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
