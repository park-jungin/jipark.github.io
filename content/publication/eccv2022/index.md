---
title: 'PointFix: Learning to Fix Domian Bias for Robust Online Stereo Adaptation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kwonyoung Kim
  - admin
  - Jiyoung Lee
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-07-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV 2022*

abstract: Online stereo adaptation tackles the domain shift problem, caused by different environments between synthetic (training) and real (test) datasets, to promptly adapt stereo models in dynamic real-world applications such as autonomous driving. However, previous methods often fail to counteract particular regions related to dynamic objects with more severe environmental changes. To mitigate this issue, we propose to incorporate an auxiliary point-selective network into a meta-learning framework, called PointFix, to provide a robust initialization of stereo models for online stereo adaptation. In a nutshell, our auxiliary network learns to fix local variants intensively by effectively back-propagating local information through the meta-gradient for the robust initialization of the baseline model. This network is model-agnostic, so can be used in any kind of architectures in a plug-and-play manner. We conduct extensive experiments to verify the effectiveness of our method under three adaptation settings such as short-, mid-, and long-term sequences. Experimental results show that the proper initialization of the base stereo model by the auxiliary network enables our learning paradigm to achieve state-of-the-art performance at inference.

# Summary. An optional shortened abstract.
summary: European Conference on Computer Vision (ECCV) 2022

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980557.pdf'
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
