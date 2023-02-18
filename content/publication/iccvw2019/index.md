---
title: 'Video Summarization by Learning Relationships between Action and Scene'

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
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-07-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-10-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF International Conference on Computer Vision Workshop*
publication_short: In *ICCVW 2019* (3rd place)

abstract: We propose a novel deep architecture for video summarization in untrimmed videos that simultaneously recognizes action and scene classes for every video segments. Our networks accomplish this through a multi-task fusion approach based on two types of attention modules to explore semantic correlations between action and scene in the videos. The proposed networks consist of the feature embedding networks and attention inference networks to stochastically leverage the inferred action and scene feature representations. Additionally, we design a new center loss function that learns the feature representations by enforcing to minimize the intra-class variations and to maximize the interclass variations. Our model achieves a score of 0.8409 for summarization and accuracy of 0.7294 for action and scene recognition on test set of CoVieW’19 dataset, which is ranked 3rd.



# Summary. An optional shortened abstract.
summary: IEEE/CVF International Conference on Computer Vision Workshop (ICCVW) 2019

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content_ICCVW_2019/papers/CoView/Park_Video_Summarization_by_Learning_Relationships_between_Action_and_Scene_ICCVW_2019_paper.pdf'
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
