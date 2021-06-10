---
title: "𝕏 Resolution Correspondence Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shuda Li
- Kai Han
- David Mitchell
- Rigas Kouskouridas

# # Author notes (optional)
# author_notes:
- "University of Oxford"
- "XYZ Reality"
- "University of Oxford"
- "XYZ Reality"
- "XYZ Reality"

date: "2020-03-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv* (in review)
publication_short: In *arXiv* (in review)

abstract: In this paper, we aim at establishing accurate dense correspondences between a pair of images with overlapping field of view under challenging illumination variation, viewpoint changes, and style differences. Through an extensive ablation study of the state-of-the-art correspondence networks, we surprisingly discovered that the widely adopted 4D correlation tensor and its related learning and processing modules could be de-parameterised and removed from training with merely a minor impact over the final matching accuracy. Disabling these computational expensive modules dramatically speeds up the training procedure and allows to use 4 times bigger batch size, which in turn compensates for the accuracy drop. Together with a multi-GPU inference stage, our method facilitates the systematic investigation of the relationship between matching accuracy and up-sampling resolution of the native testing images from 1280 to 4K. This leads to discovery of the existence of an optimal resolution 𝕏 that produces accurate matching performance surpassing the state-of-the-art methods particularly over the lower error band on public benchmarks for the proposed network.

# Summary. An optional shortened abstract.
summary: In this paper we investigate state-of-the-art dense correspondence networks and their ability to process high-resolution images. This leads to discovery of the existence of an optimal resolution 𝕏.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.09842.pdf'
url_code: 'https://github.com/XYZ-R-D/xrcnet'
url_dataset: ''
url_poster: ''
url_project: 'https://xyz-r-d.github.io/xrcnet/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Geometry match between 3D model and image of the Radcliff Camera in Oxford'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - [example]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).