---
title: "Safety in multi-assembly via paths appearing in all path covers of a DAG"
authors:
- admin
- Brendan Mumey
- Edin Husic
- Romeo Rizzi
- Massimo Cairo
- Kristoffer Sahlin
- Alexandru I. Tomescu
date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE/ACM Transactions on Computational Biology and Bioinformatics
publication_short: In TCBB

abstract:  "A multi-assembly problem asks to reconstruct multiple genomic sequences from mixed reads sequenced from all of them.
Standard formulations of such problems model a solution as a path cover in a directed acyclic graph, namely a set of paths that
together cover all vertices of the graph.

Since multi-assembly problems admit multiple solutions in practice, we consider an approach commonly used in standard genome
assembly: output only partial solutions (contigs, or safe paths), that appear in all path cover solutions. We study constrained path
covers, a restriction on the path cover solution that incorporate practical constraints arising in multi-assembly problems. We give
efficient algorithms finding all maximal safe paths for constrained path covers.

We compute the safe paths of splicing graphs constructed from transcript annotations of different species. Our algorithms run in less
than 15 seconds per species and report RNA contigs that are over 99% precise and are up to 8 times longer than unitigs. Moreover,
RNA contigs cover over 70% of the transcripts and their coding sequences in most cases. With their increased length to unitigs, high
precision, and fast construction time, maximal safe paths can provide a better base set of sequences for transcript assembly programs."

# Summary. An optional shortened abstract.
summary: "We show how to compute maximal safe path for constrained path covers, with applications to multi-assembly. Our experiments in transcript assembly show that max. safe paths are very precise and cover 70% of transcripts."


tags:
- Journal Publication
- TCBB
featured: true

links: []
url_pdf: ''
url_code: 'https://github.com/algbio/SafePathsRNAPC'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
math : true
---
