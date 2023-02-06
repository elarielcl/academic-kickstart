---
title: "A Safety Framework for Flow Decomposition Problems via Integer Linear Programming"
authors:
- Fernando H. C. Dias
- admin
- Lucia Williams
- Brendan Mumey
- Alexandru I. Tomescu
date: "2023-01-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arXiv
publication_short: In arXiv

abstract:  "Many important problems in Bioinformatics (e.g., assembly or multi-assembly) admit multiple solutions, while the final objective is to report only one. A common approach to deal with this uncertainty is finding *safe* partial solutions (e.g., contigs) which are common to all solutions. Previous research on safety has focused on polynomially-time solvable problems, whereas many successful and natural models are NP-hard to solve, leaving a lack of *safety tools* for such problems. We propose the first method for computing all safe solutions for an NP-hard problem, *minimum flow decomposition*. We obtain our results by developing a *safety test* for paths based on a general Integer Linear Programming (ILP) formulation. Moreover, we provide implementations with practical optimizations aimed to reduce the total ILP time, the most efficient of these being based on a recursive group-testing procedure.
Experimental results on the transcriptome datasets of Shao and Kingsford (TCBB, 2017) show that all safe paths for minimum flow decompositions correctly recover up to 90% of the full RNA transcripts, which is at least 25% more than previously known safe paths, such as (Caceres et al. TCBB, 2021), (Zheng et al., RECOMB 2021), (Khan et al., RECOMB 2022, ESA 2022). Moreover, despite the NP-hardness of the problem,  we can report all safe paths for 99.8% of the over 27,000 non-trivial graphs of this dataset in only 1.5 hours. Our results suggest that, on perfect data, there is less ambiguity than thought in the notoriously hard RNA assembly problem"

# Summary. An optional shortened abstract.
summary: "We propose the first method for computing all safe solutions for an NP-hard problem, *minimum flow decomposition*. We obtain our results by developing a *safety test* for paths based on a general Integer Linear Programming (ILP) formulation. Moreover, we provide implementations with practical optimizations aimed to reduce the total ILP time. Experimental results on the transcriptome datasets of Shao and Kingsford (TCBB, 2017) show that all safe paths for minimum flow decompositions correctly recover up to 90% of the full RNA transcripts, which is at least 25% more than previously known safe paths. Moreover, despite the NP-hardness of the problem,  we can report all safe paths for 99.8% of the over 27,000 non-trivial graphs of this dataset in only 1.5 hours."


tags:
- Preprint
- arXiv
featured: false

links: []
url_pdf: 'https://arxiv.org/pdf/2301.13245.pdf'
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
  caption: 'Path safety test encoded as ILP'
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
