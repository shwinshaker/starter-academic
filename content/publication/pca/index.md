---
title: "Average Approximates First Principal Component? An Empirical Analysis on Representations from Neural Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zihan Wang
- admin
- Jingbo Shang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *preprint*
publication_short: In *preprint*

abstract: Contextualized representations based on neural language models have furthered the state of the art in various NLP tasks. Despite its great success, the nature of such representations remains a mystery. In this paper, we present an empirical property of these representations --- *average ~ first principal component*. Specifically, experiments show that the average of these representations shares almost the same direction as the first principal component of the matrix whose columns are these representations. We believe this explains why the average representation is always a simple yet strong baseline. Our further examinations show that this property also holds in more challenging scenarios, for example, when the representations are from a model right after its random initialization. Therefore, we conjecture that this property is intrinsic to the distribution of representations and not necessarily related to the input structure. We realize that these representations empirically follow a normal distribution for each dimension, and by assuming this is true, we demonstrate that the empirical property can be in fact derived mathematically.

# Summary. An optional shortened abstract.
summary: The average of contextualized representations shares almost the same direction as the first principal component of the matrix whose columns are these representations. We believe this explains why the average representation is always a simple yet strong baseline.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Video
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '' # 'Our method can save about 50% training time for ResNet.'
  focal_point: "smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" # example
---

<!--
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
-->

<!--
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->
