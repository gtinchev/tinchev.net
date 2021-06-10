---
title: "SKD: "

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

date: "2020-03-11T00:00:00Z"
doi: "10.1109/LRA.2021.3065224"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Robotics and Automation Letters/IEEE International Conference on Robotics and Automation*
publication_short: In *RAL/ICRA*

abstract: We present SKD, a novel keypoint detector that uses saliency to determine the best candidates from a point cloud for tasks such as registration and reconstruction. The approach can be applied to any differentiable deep learning descriptor by using the gradients of that descriptor with respect to the 3D position of the input points as a measure of their saliency. The saliency is combined with the original descriptor and context information in a neural network, which is trained to learn robust keypoint candidates. The key intuition behind this approach is that keypoints are not extracted solely as a result of the geometry surrounding a point, but also take into account the descriptor's response. The approach was evaluated on two large LIDAR datasets - the Oxford RobotCar dataset and the KITTI dataset, where we obtain up to 50% improvement over the state-of-the-art in both matchability and repeatability. When performing sparse matching with the keypoints computed by our method we achieve a higher inlier ratio and faster convergence.

# Summary. An optional shortened abstract.
summary: In this paper we propose a new method of extracing keypoints from point clouds using saliency information from a differentiable descriptor.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1912.04943.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.youtube.com/watch?v=Xhvg7-s9g80'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=Wx6FEWCgWDk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Top-down view of keypoints (blue) extracted from a point cloud (red) for two competitors and SKD.'
  focal_point: "Right"
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
