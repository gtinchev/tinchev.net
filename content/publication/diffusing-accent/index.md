---
title: "Diffusion-based accent modelling in speech synthesis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kamil Deja
- admin
- Marta Czarnowska
- Marius Cotescu
- Jasha Droppo

# Author notes (optional)
author_notes:
- "Warsaw University of Technology"
- "Amazon Research"
- "Amazon Research"
- "Amazon Research"
- "Amazon Research"

date: "2023-06-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Interspeech*
publication_short: In *Interspeech*

abstract: In this work, we introduce a diffusion-based text-to-speech (TTS) system for accent modelling. TTS systems have become a natural part of our surroundings. Nevertheless, because of the complexity of accent modelling, recent state-of-the-art solutions mainly focus on the most common variants of each language. In this work, we propose to address this issue with a newly proposed diffusion generative model (DDGM). We first show how we can adapt DDGMs to the problem of accent modelling. We evaluate and compare this approach with a recent state-of-the-art solution, showing its superiority in modelling six different English accents. On top of our TTS system, we introduce a novel accent conversion method, where using the saliency map technique, we remove source accent-related features and replace them with the target ones through the diffusion process. We show that with this approach, we can perform accent conversion without a need for any additional speech information such as phonemes or text.

# Summary. An optional shortened abstract.
summary: In this paper we model accents by adding extra conditioning to a diffusion model. We also convert the accent by using saliency to achieve accent inpainting in melspectrograms.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://assets.amazon.science/5f/ec/df57a8274fc8bec4e1a59f5dc6e8/diffusion-based-accent-modelling-in-speech-synthesis.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://bit.ly/diffuse-accent'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Architecture of the accented diffusion model'
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
