---
title: "Learning to See the Wood for the Trees: Deep Laser Localization in Urban and Natural Environments on a CPU"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Adrian Penate-Sanchez
- Maurice Fallon

# # Author notes (optional)
# author_notes:
- "University of Oxford"
- "University of Oxford"
- "University of Oxford"

date: "2019-01-19T00:00:00Z"
doi: "10.1109/LRA.2019.2895264"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Robotics and Automation Letters/IEEE International Conference on Robotics and Automation*
publication_short: In *RAL/ICRA*

abstract: Localization in challenging, natural environments, such as forests or woodlands, is an important capability for many applications from guiding a robot navigating along a forest trail to monitoring vegetation growth with handheld sensors. In this letter, we explore laser-based localization in both urban and natural environments, which is suitable for online applications. We propose a deep learning approach capable of learning meaningful descriptors directly from three-dimensional point clouds by comparing triplets (anchor, positive, and negative examples). The approach learns a feature space representation for a set of segmented point clouds that are matched between a current and previous observations. Our learning method is tailored toward loop closure detection resulting in a small model that can be deployed using only a CPU. The proposed learning method would allow the full pipeline to run on robots with limited computational payloads, such as drones, quadrupeds, or Unmanned Ground Vehicles (UGVs).

# Summary. An optional shortened abstract.
summary: In this paper we propose a new method for localization that learns to match LIDAR segments in challenging environments.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1902.10194.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://ori.ox.ac.uk/labs/drs/global-lidar-localization/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=RmNLmfhwrIM'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'PCA visualization of the final layer after training. Each sample represents a single 3D segments, coloured by class.'
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