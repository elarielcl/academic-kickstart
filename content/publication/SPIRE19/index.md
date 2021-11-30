---
title: "Faster Repetition-Aware Compressed Suffix Trees Based on Block Trees"
authors:
- admin
- Gonzalo Navarro
date: "2019-10-07T12:13:46Z"
doi: "https://doi.org/10.1007/978-3-030-32686-9_31"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-07T12:13:46Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In String *Processing and Information Retrieval - 26th International Symposium, SPIRE 2019*
publication_short: In *SPIRE 2019*

abstract:  "Suffix trees are a fundamental data structure in stringology, but their space usage, though linear, is an important problem in applications. We design and implement a new compressed suffix tree targeted to highly repetitive texts, such as large genomic collections of the same species. Our suffix tree builds on Block Trees, a recent Lempel-Ziv-bounded data structure that captures the repetitiveness of its input. We use Block Trees to compress the topology of the suffix tree, and augment the Block Tree nodes with data that speeds up suffix tree navigation.

Our compressed suffix tree is slightly larger than previous repetition-aware suffix trees based on grammars, but outperforms them in time, often by orders of magnitude. The component that represents the tree topology achieves a speed comparable to that of general-purpose compressed trees, while using 2–10 times less space, and might be of independent interest."

# Summary. An optional shortened abstract.
summary: "New Repetition-Aware Compressed Suffix Tree. Slightly larger than state-of-the-art, but outperforms them in time, often by orders of magnitude."


tags:
- Conference Publication
- SPIRE
- Compressed Data Structures
featured: false

links: []
url_pdf: 'https://arxiv.org/pdf/1902.03274.pdf'
url_code: 'https://github.com/elarielcl/MinimalistBT-CST'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/spire2019.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
