---
title: "Predicting Alignment Risk to Prevent Localization Failure"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Simona Nobili
- admin
- Maurice Fallon

# Author notes (optional)
author_notes:
- "University of Edinburgh"
- "University of Oxford"
- "University of Oxford"

date: "2018-05-25T00:00:00Z"
doi: "10.1109/ICRA.2018.8462890"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA*

abstract: During localization and mapping the success of point cloud registration can be compromised when there is an absence of geometric features or constraints in corridors or across doorways, or when the volumes scanned only partly overlap, due to occlusions or constrictions between subsequent observations. This work proposes a strategy to predict and prevent laser-based localization failure. Our solution relies on explicit analysis of the point cloud content prior to registration. A model predicting the risk of a failed alignment is learned by analysing the degree of spatial overlap between two input point clouds and the geometric constraints available within the region of overlap. We define a novel measure of alignability for these constraints. The method is evaluated against three real-world datasets and compared to baseline approaches. The experiments demonstrate how our approach can help improve the reliability of laser-based localization during exploration of unknown and cluttered man-made environments.

# Summary. An optional shortened abstract.
summary: In this paper we propose a novel method for assessing the risk of registration failure when aligning two point clouds.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.robots.ox.ac.uk/~mobile/Papers/2018ICRA_nobili.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=k-TPfCObxmY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Side view of robot crossing doors where misalignment of point clouds is common.'
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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->