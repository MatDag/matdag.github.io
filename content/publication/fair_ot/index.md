---
title: 'Optimal Transport under Group Fairness Constraints '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Linus Bleistein
  - Mathieu Dagréou
  - Francisco Andrade
  - Thomas Boudou
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
publication: In arXiv
# publication_short: In *ICW*

abstract:  Ensuring fairness in matching algorithms is a key challenge in allocating scarce resources and positions. Focusing on Optimal Transport (OT), we introduce a novel notion of group fairness requiring that the probability of matching two individuals from any two given groups in the OT plan satisfies a predefined target. We first propose FairSinkhorn, a modified Sinkhorn algorithm to compute perfectly fair transport plans efficiently. Since exact fairness can significantly degrade matching quality in practice, we then develop two relaxation strategies. The first one involves solving a penalised OT problem, for which we derive novel finite-sample complexity guarantees. This result is of independent interest as it can be generalized to arbitrary convex penalties. Our second strategy leverages bilevel optimization to learn a ground cost that induces a fair OT solution, and we establish a bound guaranteeing that the learned cost yields fair matchings on unseen data. Finally, we present empirical results that illustrate the trade-offs between fairness and performance.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2601.07144.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2601.07144

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
