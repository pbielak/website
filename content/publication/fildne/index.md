---
title: "FILDNE: A Framework for Incremental Learning of Dynamic Networks Embeddings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kamil Tagowski
- Maciej Falkiewicz
- Tomasz Kajdanowicz
- Nitesh V. Chawla

date: "2020-11-19T00:00:00Z"
doi: "10.1016/j.knosys.2021.107453"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Knowledge-Based Systems
publication_short: KBS

abstract: Representation learning on graphs has emerged as a powerful mechanism to automate feature vector generation for downstream machine learning tasks. The advances in representation on graphs have centered on both homogeneous and heterogeneous graphs, where the latter presenting the challenges associated with multi-typed nodes and/or edges. In this paper, we consider the additional challenge of evolving graphs. We ask the question of whether the advances in representation learning for static graphs can be leveraged for dynamic graphs and how? It is important to be able to incorporate those advances to maximize the utility and generalization of methods. To that end, we propose the Framework for Incremental Learning of Dynamic Networks Embedding (FILDNE), which can utilize any existing static representation learning method for learning node embeddings while keeping the computational costs low. FILDNE integrates the feature vectors computed using the standard methods over different timesteps into a single representation by developing a convex combination function and alignment mechanism. Experimental results on several downstream tasks, over seven real-world datasets, show that FILDNE is able to reduce memory (up to 6x) and computational time (up to 50x) costs while providing competitive quality measure gains (e.g., improvements up to 19 pp AUC on link prediction and up to 33 pp mAP on graph reconstruction) with respect to the contemporary methods for representation learning on dynamic graphs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1904.03423.pdf'
url_code: 'https://gitlab.com/fildne/fildne'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'FILDNE applied on snapshots embeddings'
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
