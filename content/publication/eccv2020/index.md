---
title: 'SumGraph: Video Summarization via Recursive Graph Modeling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jiyoung Lee
  - Ig-Jae Kim
  - Kwanghoon Sohn

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-07-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV 2020*

abstract: The goal of video summarization is to select keyframes that are visually diverse and can represent a whole story of an input video. State-of-the-art approaches for video summarization have mostly regarded the task as a frame-wise keyframe selection problem by aggregating all frames with equal weight. However, to find informative parts of the video, it is necessary to consider how all the frames of the video are related to each other. To this end, we cast video summarization as a graph modeling problem. We propose recursive graph modeling networks for video summarization, termed SumGraph, to represent a relation graph, where frames are regarded as nodes and nodes are connected by semantic relationships among frames. Our networks accomplish this through a recursive approach to refine an initially estimated graph to correctly classify each node as a keyframe by reasoning the graph representation via graph convolutional networks. To leverage SumGraph in a more practical environment, we also present a way to adapt our graph modeling in an unsupervised fashion. With SumGraph, we achieved state-of-theart performance on several benchmarks for video summarization in both supervised and unsupervised manners.

# Summary. An optional shortened abstract.
summary: European Conference on Computer Vision (ECCV) 2020

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700647.pdf'
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
