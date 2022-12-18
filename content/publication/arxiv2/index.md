---
title: "Parameterized Algorithms for String Matching to DAGs: Funnels and Beyond"
authors:
- admin
date: "2022-12-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arXiv
publication_short: In arXiv

abstract:  "The problem of String Matching to Labeled Graphs (SMLG) asks to find all the paths in a labeled graph $G = (V, E)$ whose spellings match that of an input string $S \\in \\Sigma^m$. SMLG can be solved in quadratic $O(m|E|)$ time [Amir et al., JALG], which was proven to be optimal by a recent lower bound conditioned on SETH [Equi et al., ICALP 2019]. The lower bound states that no strongly subquadratic time algorithm exists, even if restricted to directed acyclic graphs (DAGs).
In this work we present the first parameterized algorithms for SMLG in DAGs. Our parameters capture the topological structure of $G$. All our results are derived from a generalization of the Knuth-Morris-Pratt algorithm [Park and Kim, CPM 1995] optimized to work in time proportional to the number of prefix-incomparable matches.
To obtain the parameterization in the topological structure of $G$, we first study a special class of DAGs called funnels [Millani et al., JCO] and generalize them to $k$-funnels and the class $ST_k$. We present several novel characterizations and algorithmic contributions on both funnels and their generalizations."

# Summary. An optional shortened abstract.
summary: "We present the first parameterized algorithms for SMLG in DAGs, derived from a generalization of the Knuth-Morris-Pratt algorithm optimized to work in time proportional to the number of prefix-incomparable matches. We obtain parameterizations in the topological structure of $G$, by studying a special class of DAGs called funnels and generalizing them to $k$-funnels and the class $ST_k$."


tags:
- Preprint
- arXiv
featured: true

links: []
url_pdf: 'https://arxiv.org/pdf/2212.07870.pdf'
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
  caption: 'Two prefixes are incomparable iff they are not the LCA of one another in the failure tree'
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
