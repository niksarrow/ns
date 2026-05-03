---
title: "Learn to Unlearn in Large Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rituraj Singh

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2026-03-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2026 IEEE International Conference on Acoustics, Speech, and Signal Processing
publication_short: In *ICASSP*

abstract: Large Language Models are trained on massive corpora, allowing them to acquire extensive linguistic and factual knowledge. The training data often contains sensitive and copyrighted information, leading to concerns about unintended memorization and privacy leakage. Model unlearning aims to remove the influence of specific data without compromising model performance or general knowledge. We introduce a novel unlearning framework based on reinforcement learning, leveraging Group Relative Policy Optimization to effectively forget sensitive content. We deploy a two-stage approach starting with cold-start fine-tuning using curated synthetic data to initialize the model. We introduce carefully designed reward functions, combining lightweight models and heuristics, to guide the unlearning process while maintaining computational efficiency in RL training. Extensive experiments on the TOFU dataset show that our method outperforms prior unlearning approaches, achieving a 47% model utility improvement and 0.023 ROUGE on forget set while retaining performance on retain set and mitigating hallucinations.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11464235'
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
  caption: ''
  focal_point: ""
  preview_only:  false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
