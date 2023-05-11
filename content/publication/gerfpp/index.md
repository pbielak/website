---
title: "A deeper look at Graph Embedding RetroFitting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jakub Binkowski
- Albert Sawczyn
- Katsiaryna Viarenich
- Daria Puchalska
- Tomasz Kajdanowicz

date: "2023-04-01T00:00:00Z"
doi: "10.1016/j.jocs.2023.101979"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Science
publication_short: JoCS

abstract: Representation learning for graphs has attracted increasing attention in recent years. In particular, this work is focused on a new problem in this realm which is learning attributed graph embeddings. The setting considers how to update existing node representations from structural graph embedding methods when some additional node attributes are given. Recently, Graph Embedding RetroFitting (GERF) was proposed to this end – a method that delivers a compound node embedding that follows both the graph structure and attribute space similarity. It uses existing structural node embeddings and retrofits them according to the neighborhood defined by the node attributes space (by optimizing the invariance loss and the attribute neighbor loss). In order to refine GERF method, we aim to include the simplification of the objective function and provide an algorithm for automatic hyperparameter estimation, whereas the experimental scenario is extended by a more robust hyperparameter search for all considered methods and a link prediction problem for evaluation of node embeddings.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S187775032300039X'
url_code: 'https://github.com/graphml-lab-pwr/gerf'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Graph Embedding RetroFitting pipeline'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- phd

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!--{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).-->
