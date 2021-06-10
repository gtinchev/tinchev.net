---
title: "Online LiDAR-SLAM for Legged Robots with Robust Registration and Deep-Learned Loop Closure"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Milad Ramezani
- admin
- Egor Iuganov
- Maurice Fallon

# Author notes (optional)
author_notes:
- "University of Oxford"
- "University of Oxford"
- "University of Oxford"
- "University of Oxford"

date: "2020-01-01T00:00:00Z"
doi: "10.1109/ICRA40945.2020.9196769"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA*

abstract: In this paper, we present a 3D factor-graph LiDAR-SLAM system which incorporates a state-of-the-art deeply learned feature-based loop closure detector to enable a legged robot to localize and map in industrial environments. Point clouds are accumulated using an inertial-kinematic state estimator before being aligned using ICP registration. To close loops we use a loop proposal mechanism which matches individual segments between clouds. We trained a descriptor offline to match these segments. The efficiency of our method comes from carefully designing the network architecture to minimize the number of parameters such that this deep learning method can be deployed in real-time using only the CPU of a legged robot, a major contribution of this work. The set of odometry and loop closure factors are updated using pose graph optimization. Finally we present an efficient risk alignment prediction method which verifies the reliability of the registrations. Experimental results at an industrial facility demonstrated the robustness and flexibility of our system, including autonomous following paths derived from the SLAM map.

# Summary. An optional shortened abstract.
summary: In this paper we propose a new SLAM method with a novel risk alignment prediction method that verifies the registration.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2001.10249.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=djf7vGtf7CA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Top-down view of the trajectory produced by the proposed SLAM method'
  focal_point: "Top"
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