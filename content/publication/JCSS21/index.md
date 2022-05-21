---
title: "Block Trees"
authors:
- Djamal Belazzougui
- admin
- Travis Gagie
- Pawel Gawrychowski
- Juha Kärkkäinen
- Gonzalo Navarro
- Alberto Ordóñez
- Simon J. Puglisi
- Yasuo Tabei
date: "2020-11-21T00:00:00Z"
doi: "https://doi.org/10.1016/j.jcss.2020.11.002"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In the Journal of Computer and System Sciences
publication_short: In JCSS

abstract:  "Let string $S[1..n]$ be parsed into $z$ phrases by the Lempel-Ziv algorithm. The corresponding compression algorithm encodes $S$ in $O(z)$ space, but it does not support random access to $S$. We introduce a data structure, the block tree, that represents $S$ in $O(z \\log(n/z))$ space and extracts any symbol of $S$ in time $O(\\log(n/z))$, among other space-time tradeoffs. The structure also supports other queries that are useful for building compressed data structures on top of $S$. Further, block trees can be built in linear time and in a scalable manner. Our experiments show that block trees offer relevant space-time tradeoffs compared to other compressed string representations for highly repetitive strings."

# Summary. An optional shortened abstract.
summary: "We introduce a data structure, the block tree, that represents $S$ in $O(z \\log(n/z))$ space and extracts any symbol of $S$ in time $O(\\log(n/z))$, among other space-time tradeoffs. The structure also supports other queries that are useful for building compressed data structures on top of $S$."


tags:
- Journal Publication
- JCSS
featured: true

links: []
url_pdf: 'files/jcss20.pdf'
url_code: 'https://github.com/elarielcl/MinimalistBlockTrees'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Block Tree'
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
