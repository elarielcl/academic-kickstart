---
title: "Chaining of Maximal Exact Matches in Graphs"
authors:
- Nicola Rizzo
- admin
- Veli Makinen
date: "2023-02-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arXiv
publication_short: In arXiv

abstract:  "We study the problem of finding maximal exact matches (MEMs) between a query string $Q$ and a labeled directed acyclic graph (DAG) $G=(V,E,\\ell)$ and subsequently co-linearly chaining these matches. We show that it suffices to compute MEMs between node labels and $Q$ (node MEMs) to encode full MEMs. Node MEMs can be computed in linear time and we show how to co-linearly chain them to solve the Longest Common Subsequence (LCS) problem between $Q$ and $G$. Our chaining algorithm is the first to consider a symmetric formulation of the chaining problem in graphs and runs in $O(k^2|V| + |E| + kN\\log N)$ time, where $k$ is the width (minimum number of paths covering the nodes) of $G$, and $N$ is the number of node MEMs. We then consider the problem of finding MEMs when the input graph is an indexable elastic founder graph (subclass of labeled DAGs studied by Equi et al., Algorithmica 2022). For arbitrary input graphs, the problem cannot be solved in truly sub-quadratic time under SETH (Equi et al., ICALP 2019). We show that we can report all MEMs between $Q$ and an indexable elastic founder graph in time $O(nH^2 + m + M_\\kappa)$, where $n$ is the total length of node labels, $H$ is the maximum number of nodes in a block of the graph, $m = |Q|$, and $M_\\kappa$ is the number of MEMs of length at least $\\kappa$"

# Summary. An optional shortened abstract.
summary: "We show that it suffices to compute MEMs between node labels and $Q$ (node MEMs) to encode full MEMs. Node MEMs can be computed in linear time and we show how to co-linearly chain them to solve the Longest Common Subsequence (LCS) problem between $Q$ and $G$. Our chaining algorithm is the first to consider a symmetric formulation of the chaining problem in graphs and runs in $O(k^2|V| + |E| + kN\\log N)$ time, where $k$ is the width (minimum number of paths covering the nodes) of $G$, and $N$ is the number of node MEMs. We then show that we can report all MEMs between $Q$ and an indexable elastic founder graph in time $O(nH^2 + m + M_\\kappa)$, where $n$ is the total length of node labels, $H$ is the maximum number of nodes in a block of the graph, $m = |Q|$, and $M_\\kappa$ is the number of MEMs of length at least $\\kappa$"


tags:
- Preprint
- arXiv
featured: false

links: []
url_pdf: 'https://arxiv.org/pdf/2302.01748.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_doi: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Left extension of substring ACCGTA is {A, C}, thus the substring (if also in Q) is a MEM'
  focal_point: ""
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
slides: ""
---
