---
title: 'EvoGrad: A Dynamic Take on the Winograd Schema Challenge with Human Adversaries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ali Emami

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation*
publication_short: In *LREC-COLING*

abstract: "While Large Language Models (LLMs) excel at the Winograd Schema Challenge (WSC), a coreference resolution task testing common-sense reasoning through pronoun disambiguation, they struggle with instances that feature minor alterations or rewording. To address this, we introduce EvoGrad, an open-source platform that harnesses a human-in-the-loop approach to create a dynamic dataset tailored to such altered WSC instances. Leveraging ChatGPT's capabilities, we expand our task instances from 182 to 3,691, setting a new benchmark for diverse common-sense reasoning datasets. Additionally, we introduce the error depth metric, assessing model stability in dynamic tasks. Our results emphasize the challenge posed by EvoGrad: Even the best performing LLM, GPT-3.5, achieves an accuracy of 65.0% with an average error depth of 7.2, a stark contrast to human performance of 92.8% accuracy without perturbation errors. This highlights ongoing model limitations and the value of dynamic datasets in uncovering them."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
   url: https://arxiv.org/abs/2402.13372

url_pdf: ''
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
