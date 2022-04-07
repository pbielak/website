---
title: "AttrE2vec: Unsupervised Attributed Edge Representation Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tomasz Kajdanowicz
- Nitesh V. Chawla

date: "2020-12-29T00:00:00Z"
doi: "10.1016/j.ins.2022.01.048"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Information Sciences
publication_short: INS

abstract: Representation learning has overcome the often arduous and manual featurization of networks through (unsupervised) feature learning as it results in embeddings that can apply to a variety of downstream learning tasks. The focus of representation learning on graphs has focused mainly on shallow (node-centric) or deep (graph-based) learning approaches. While there have been approaches that work on homogeneous and heterogeneous networks with multi-typed nodes and edges, there is a gap in learning edge representations. This paper proposes a novel unsupervised inductive method called AttrE2Vec, which learns a low-dimensional vector representation for edges in attributed networks. It systematically captures the topological proximity, attributes affinity, and feature similarity of edges. Contrary to current advances in edge embedding research, our proposal extends the body of methods providing representations for edges, capturing graph attributes in an inductive and unsupervised manner. Experimental results show that, compared to contemporary approaches, our method builds more powerful edge vector representations, reflected by higher quality measures (AUC, accuracy) in downstream tasks as edge classification and edge clustering. It is also confirmed by analyzing low-dimensional embedding projections. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.14727.pdf'
url_code: 'https://github.com/attre2vec/attre2vec'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'AttrE2vec pipeline'
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
