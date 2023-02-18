---
title: 'Cross-Domain Grouping and Alignment for Domain Adaptive Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Minsu Kim
  - Sunghun Joung
  - Seungryong Kim
  - admin
  - Ig-Jae Kim
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2020-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2021*

abstract: Existing techniques to adapt semantic segmentation networks across source and target domains within deep convolutional neural networks (CNNs) deal with all the samples from the two domains in a global or category-aware manner. They do not consider an inter-class variation within the target domain itself or estimated category, providing the limitation to encode the domains having a multi-modal data distribution. To overcome this limitation, we introduce a learnable clustering module, and a novel domain adaptation framework, called cross-domain grouping and alignment. To cluster the samples across domains with an aim to maximize the domain alignment without forgetting precise segmentation ability on the source domain, we present two loss functions, in particular, for encouraging semantic consistency and orthogonality among the clusters. We also present a loss so as to solve a class imbalance problem, which is the other limitation of the previous methods. Our experiments show that our method consistently boosts the adaptation performance in semantic segmentation, outperforming the state-of-the-arts on various domain adaptation settings.

# Summary. An optional shortened abstract.
summary: AAAI Conference on Artificial Intelligence (AAAI) 2021

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/16274/16081'
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
