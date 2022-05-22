---
title: "Faster repetition-aware compressed suffix trees based on block trees"
authors:
- admin
- Gonzalo Navarro
date: "2021-04-28T00:00:00Z"
doi: "https://doi.org/10.1016/j.ic.2021.104749"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Information and Computation
publication_short: In I&C

abstract:  "The suffix tree is a fundamental data structure in stringology, but its space usage, though linear, is an important problem in applications like Bioinformatics. We design and implement a new compressed suffix tree (CST) targeted to highly repetitive texts, such as large genomic collections of the same species. Our first contribution is to enhance the Block Tree, a data structure that captures the repetitiveness of its input sequence, to represent the topology of trees with large repeated subtrees. Our so-called Block-Tree Compressed Topology (BT-CT) data structure augments the Block Tree nodes with data that speeds up tree navigation. Our Block-Tree CST (BT-CST), in turn, uses the BT-CT to compress the topology of the suffix tree, and also replaces the sampling of the suffix array and its inverse with grammar- and/or Block-Tree-based representations of those arrays.

Our experimental results show that BT-CTs reach navigation speeds comparable to compact tree representations that are insensitive to repetitiveness, while using 2–10 times less space on the topologies of the suffix trees of repetitive collections. Our BT-CST is slightly larger than previous repetition-aware suffix trees based on grammar-compressed topologies, but outperforms them in time, often by orders of magnitude."

# Summary. An optional shortened abstract.
summary: "New Repetition-Aware Compressed Suffix Tree. Slightly larger than state-of-the-art, but outperforms them in time, often by orders of magnitude."


tags:
- Journal Publication
- I&C
featured: false

links: []
url_pdf: 'files/ic21.pdf'
url_code: 'https://github.com/elarielcl/MinimalistBT-CST'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/clei2020.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'CST concepts'
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
math : true
---
