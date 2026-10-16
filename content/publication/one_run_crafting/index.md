---
title: 'Detectability without Interference: Efficient Canary Design for Privacy Auditing in One Run'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mathieu Dagréou
  - Valentin Dorseuil
  - Mohammad Yaghini
  - Nicolas Papernot
  - Aurélien Bellet

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv
# publication_short: In *ICW*

abstract:  Privacy auditing aims to empirically assess privacy leakage in machine learning models using membership inference attacks (MIAs), and to derive lower bounds on differential privacy (DP) parameters. Standard privacy auditing inserts a sensitive sample (a canary) into many (≫100) randomized training runs, requiring the auditor to detect whether it was included in each run. In one-run auditing, many canaries are included in a single training run, avoiding the high computational cost of multi-run approaches. However, recent theory shows that canaries can interfere with one another, reducing per-canary MIA scores and thereby weakening the audit power. We propose IBIS, a framework that optimizes canaries to maximize their own score while minimizing their impact on others. IBIS combines influence-based greedy initialization with bilevel optimization, introducing a novel regularization term that encourages canaries to be orthogonal in embedding space as a proxy for reducing interference. We propose an efficient bilevel algorithm that incrementally updates a single model at each canary update, avoiding the need to retrain the model from scratch after every update. Experiments show that IBIS offers a better performance-cost trade-off than existing canary crafting approaches, improving MIA metrics while reducing computational cost by up to two orders of magnitude. 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2605.27292.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2605.27292

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
