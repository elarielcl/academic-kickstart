---
title: "Width Helps and Hinders Splitting Flows"
authors:
- admin
- Massimo Cairo
- Andreas Grigorjew
- Shahbaz Khan
- Brendan Mumey
- Romeo Rizzi
- Alexandru I. Tomescu
- Lucia Williams
date: "2022-09-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In European Symposium on Algorithms (ESA 2022)
publication_short: In ESA 2022

abstract:  "Minimum flow decomposition (MFD) is the NP-hard problem of finding a smallest decomposition of a network flow $X$ on directed graph $G$ into weighted source-to-sink paths whose superposition equals $X$. We focus on a common formulation of the problem where the path weights must be non-negative integers and also on a new variant where these weights can be negative. We show that, for acyclic graphs, considering the width of the graph (the minimum number of $s$-$t$ paths needed to cover all of its edges) yields advances in our understanding of its approximability. For the non-negative version, we show that a popular heuristic is a $O( \\log |X|)$-approximation ($|X|$ being the total flow of $X$) on graphs satisfying two properties related to the width (satisfied by e.g., series-parallel graphs), and strengthen its worst-case approximation ratio from $\\Omega(\\sqrt{m})$ to $\\Omega(m / \\log m)$ for sparse graphs, where $m$ is the number of edges in the graph. For the negative version, we give a $(\\lceil \\log \\Vert X \\Vert \\rceil +1)$-approximation ($\\Vert X \\Vert$ being the maximum absolute value of $X$ on any edge) using a power-of-two approach, combined with parity fixing arguments and a decomposition of unitary flows ($\\Vert X \\Vert \\leq 1$) into  at most width paths. We also disprove a conjecture about the linear independence of minimum (non-negative) flow decompositions posed by Kloster et al. [ALENEX 2018], but show that its useful implication (polynomial-time assignments of weights to a given set of paths to decompose a flow) holds for the negative version."

# Summary. An optional shortened abstract.
summary: "We show that, for acyclic graphs, considering the width of the graph yields advances in our understanding of its approximability. For the non-negative version, we show that a popular heuristic is a $O( \\log |X|)$-approximation on graphs satisfying two properties related to the width (satisfied by e.g., series-parallel graphs), and strengthen its worst-case approximation ratio for sparse graphs. For the negative version, we give a $(\\lceil \\log \\Vert X \\Vert \\rceil +1)$-approximation using a power-of-two approach, combined with parity fixing arguments and a decomposition of unitary flows ($\\Vert X \\Vert \\leq 1$) into  at most width paths."


tags:
- Conference Publication
- ESA
featured: false

links: []
url_pdf: 'https://arxiv.org/abs/2207.02136'
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
  caption: 'Flow decomposition using negative weights can yield to a smaller solution'
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
