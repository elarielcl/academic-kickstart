---
title: "Safety and Completeness in Flow Decompositions for RNA Assembly"
authors:
- Shahbaz Khan
- Milla Kortelainen
- admin
- Lucia Williams
- Alexandru I. Tomescu
date: "2022-05-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In International Conference on Research in Computational Molecular Biology (RECOMB 2022)
publication_short: In RECOMB 2022

abstract:  "Decomposing a network flow into weighted paths is a problem with numerous applications, ranging from networking, transportation planning to bioinformatics. In some applications we look for any decomposition that is optimal with respect to some property, such as number of paths used, robustness to edge deletion, or length of the longest path. However, in many bioinformatic applications, we seek a specific decomposition where the paths correspond to some underlying data that generated the flow. For realistic inputs, no optimization criteria can be guaranteed to uniquely identify the correct decomposition. Therefore, we propose to instead report the {\em safe} paths, which are subpaths of at least one path in every flow decomposition. 

Recently, Ma, Zheng, and Kingsford [WABI 2020] addressed the existence of multiple optimal solutions in a probabilistic framework, which is referred to as *non-identifiability*. In a follow-up work [RECOMB 2021], they gave a quadratic-time algorithm based on a *global* criterion for solving a problem called AND-Quant, which generalizes the problem of reporting whether a given path is safe.

In this work, we give the first *local* characterization of safe paths for flow decompositions in directed acyclic graphs (DAGs), leading to a practical algorithm for finding the *complete* set of safe paths. We additionally evaluated our algorithm against the trivial safe algorithms (unitigs, extended unitigs) and the popularly used heuristic (greedy-width) for flow decomposition on RNA transcripts datasets. We find that despite maintaining perfect precision the  safe and complete algorithm reports significantly higher coverage (~50% more) as compared to trivial safe algorithms. The greedy-width algorithm though reporting a better coverage, reports significantly lower precision on complex graphs (for genes expressing a large number of transcripts). Overall, our safe and complete algorithm outperforms (by ~20%) greedy-width on a unified metric (F-Score) considering both coverage and precision when the evaluated dataset has significant number of complex graphs. Moreover, it also has superior time (3-5x) and space efficiency (1.2-2.2x), resulting in a better and more practical approach for bioinformatics applications of flow decomposition."

# Summary. An optional shortened abstract.
summary: "We give the first local characterization of safe paths for flow decompositions in directed acyclic graphs (DAGs), leading to a practical algorithm for finding the complete set of safe paths. We additionally evaluated our algorithms against the trivial safe algorithms (unitigs, extended unitigs) and the popularly used heuristic (greedy-width) for flow decomposition on RNA transcripts datasets. We find that despite maintaining perfect precision the safe and complete algorithm reports significantly higher coverage as compared to trivial safe algorithms."


tags:
- Conference Publication
- RECOMB
featured: true

links: []
url_pdf: 'https://doi.org/10.48550/arXiv.2201.10372'
url_code: 'https://github.com/algbio/flow-decomposition-safety'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/recomb2022.pdf'
url_source: ''
url_video: ''
url_doi: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Safe flow subpath, which is not an extended unitig'
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
