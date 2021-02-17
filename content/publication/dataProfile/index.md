---
title: "Data Profiling for Adversarial Training: On the Ruin of Problematic Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liyuan Liu
- Jingbo Shang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *preprint*
publication_short: In *preprint*

abstract: Multiple intriguing problems hover in adversarial training, including robustness-accuracy trade-off, robust overfitting, and gradient masking, posing great challenges to both reliable evaluation and practical deployment. Here, we show that these problems share one common cause -- low quality samples in the dataset. We first identify an intrinsic property of the data called problematic score and then design controlled experiments to investigate its connections with these problems. Specifically, we find that when problematic data is removed, robust overfitting and gradient masking can be largely alleviated; and robustness-accuracy trade-off is more prominent for a dataset containing highly problematic data. These observations not only verify our intuition about data quality but also open new opportunities to advance adversarial training. Remarkably, simply removing problematic data from adversarial training, while making the training set smaller, yields better robustness consistently with different adversary settings, training methods, and neural architectures.

# Summary. An optional shortened abstract.
summary: Multiple problems in adversarial training including robustness-accuracy trade-off, robust overfitting, and gradient masking share one commnon cause -- low quality samples in the dataset.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Video
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2102.07437'
url_code: 'https://github.com/shwinshaker/RobustDataProfiling'
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
