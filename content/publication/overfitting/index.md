---
title: "Overfitting or Underfitting? Understand Robustness Drop in Adversarial Training"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zichao Li
- Liyuan Liu
- admin
- Jingbo Shang

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *preprint*
publication_short: In *preprint*

abstract: Our goal is to understand why the robustness drops after conducting adversarial training for too long. Although this phenomenon is commonly explained as overfitting, our analysis suggest that its primary cause is perturbation underfitting. We observe that after training for too long, FGSM-generated perturbations deteriorate into random noise. Intuitively, since no parameter updates are made to strengthen the perturbation generator, once this process collapses, it could be trapped in such local optima. Also, sophisticating this process could mostly avoid the robustness drop, which supports that this phenomenon is caused by underfitting instead of overfitting. In the light of our analyses, we propose APART, an adaptive adversarial training framework, which parameterizes perturbation generation and progressively strengthens them. Shielding perturbations from underfitting unleashes the potential of our framework. In our experiments, APART provides comparable or even better robustness than PGD-10, with only about 1/4 of its computational cost.


# Summary. An optional shortened abstract.
summary:  We propose APART, an adaptive adversarial training framework, which parameterizes perturbation generation and progressively strengthens them.

tags: []

# Display this page in the Featured widget?
featured: false # true

# Custom links (uncomment lines below)
# links:
# - name: Video
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2010.08034'
url_code: 'https://github.com/zichaoli/APART'
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
