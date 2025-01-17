---
title: "Chaining for Accurate Alignment of Erroneous Long Reads to Acyclic Variation Graphs"
authors:
- Jun Ma
- admin
- Leena Salmela
- Veli Mäkinen
- Alexandru I. Tomescu
date: "2022-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In biorxiv
publication_short: In biorxiv

abstract:  "Aligning reads to a variation graph is a standard task in pangenomics, with downstream applications in e.g., improving variant calling. While the vg toolkit (Garrison et al., Nature Biotechnology, 2018) is a popular aligner of short reads, GraphAligner (Rautiainen and Marschall, Genome Biology, 2020) is the state-of-the-art aligner of erroneous long reads. GraphAligner works by finding candidate read occurrences based on individually extending the best seeds of the read in the variation graph. However, a more principled approach recognized in the community is to co-linearly chain multiple seeds. We present a new algorithm to co-linearly chain a set of seeds in a string labeled acyclic graph, together with the first efficient implementation of such a co-linear chaining algorithm into a new aligner of long reads to acyclic variation graphs, GraphChainer. Compared to GraphAligner, GraphChainer aligns 12% to 17% more reads, and 21% to 28% more total read length, on real PacBio reads from human chromosomes 1 and 22. On both simulated and real data, GraphChainer aligns between 95% and 99% of all reads, and of total read length. GraphChainer is freely available at https://github.com/algbio/GraphChainer."

# Summary. An optional shortened abstract.
summary: "We present a new algorithm to co-linearly chain a set of seeds in a string labeled acyclic graph, together with the first efficient implementation of such a co-linear chaining algorithm into a new aligner of long reads to variation graphs, GraphChainer. Compared to GraphAligner, GraphChainer aligns 12% to 17% more reads, and 21% to 28% more total read length."


tags:
- PrePrint
- biorxiv
featured: true

links: []
url_pdf: 'https://doi.org/10.1101/2022.01.07.475257'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/dsb2022.pdf'
url_source: ''
url_video: ''
url_doi: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Anchors in a string labeled acyclic graph'
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
