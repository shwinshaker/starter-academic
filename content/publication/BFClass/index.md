---
title: "BFClass: A Backdoor-free Text Classification Framework"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zichao Li
- Dheeraj Mekala
- admin
- Jingbo Shang

# Author notes (optional)
# author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-05-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *EMNLP 2021*
publication_short: In *EMNLP*

abstract: Backdoor attack introduces artificial vulnerabilities into the model by poisoning a subset of the training data via injecting triggers and modifying labels. Various trigger design strategies have been explored to attack text classifiers, however, defending such attacks remains an open problem. In this work, we propose BFClass, a novel efficient backdoor-free training framework for text classification. The backbone of BFClass is a pre-trained discriminator that predicts whether each token in the corrupted input was replaced by a masked language model. To identify triggers, we utilize this discriminator to locate the most suspicious token from each training sample and then distill a concise set by considering their association strengths with particular labels. To recognize the poisoned subset, we examine the training samples with these identified triggers as the most suspicious token, and check if removing the trigger will change the poisoned model's prediction. Extensive experiments demonstrate that BFClass can identify all the triggers, remove 95% poisoned training samples with very limited false alarms, and achieve almost the same performance as the models trained on the benign training data.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Video
#   url: http://example.org

url_pdf: "https://arxiv.org/abs/2109.10855"
url_code: "https://github.com/dheeraj7596/BFClass"
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ""
url_source: ''
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
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
