---
title: "Improving RNA Assembly via Safety and Completeness in Flow Decompositions"
authors:
- Shahbaz Khan
- Milla Kortelainen
- admin
- Lucia Williams
- Alexandru I. Tomescu
date: "2022-10-25T00:00:00Z"
doi: "https://doi.org/10.1089/cmb.2022.0261"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Journal of Computational Biology
publication_short: In JCB

abstract:  "Decomposing a network flow into weighted paths is a problem with numerous applications, ranging from networking, transportation planning to bioinformatics. In some applications we look for a decomposition that is optimal with respect to some property, such as number of paths used, robustness to edge deletion, or length of the longest path. However, in many bioinformatic applications, we seek a specific decomposition where the paths correspond to some underlying data that generated the flow. In these cases, no optimization criteria guarantees the identification of the correct decomposition. Therefore, we propose to instead report the *safe* paths, which are subpaths of at least one path in every flow decomposition.

In this work, we give the first *local* characterization of safe paths for flow decompositions in directed acyclic graphs (DAGs), leading to a practical algorithm for finding the *complete* set of safe paths. Additionally, we evaluate our algorithm on RNA transcript datasets against a trivial safe algorithm (extended unitigs), the recently proposed safe paths for path covers [TCBB 2021] and the popular heuristic *greedy-width*. One the one hand, we found that besides maintaining perfect precision, our safe and complete algorithm reports significantly higher coverage ($\approx 50\%$ more) as compared to the other safe algorithms. On the other hand, the greedy-width algorithm although reporting a better coverage, it also reports significantly lower precision on complex graphs (for genes expressing a large number of transcripts). Overall, our safe and complete algorithm outperforms (by $\approx 20\%$) greedy-width on a unified metric (F-Score) considering both coverage and precision when the evaluated dataset has a significant number of complex graphs. Moreover, it also has a superior time ($4-5\times$) and space performance ($1.2-2.2\times$), resulting in a better and more practical approach for bioinformatics applications of flow decomposition."

# Summary. An optional shortened abstract.
summary: "We give the first *local* characterization of safe paths for flow decompositions in directed acyclic graphs (DAGs), leading to a practical algorithm for finding the *complete* set of safe paths. Additionally, we evaluate our algorithm on RNA transcript datasets against a trivial safe algorithm (extended unitigs), the recently proposed safe paths for path covers [TCBB 2021] and the popular heuristic *greedy-width*. Our safe and complete algorithm outperforms (by $\approx 20\%$) greedy-width on a unified metric (F-Score) considering both coverage and precision when the evaluated dataset has a significant number of complex graphs."


tags:
- Journal Publication
- JCB
featured: true

links: []
url_pdf: 'https://www.liebertpub.com/doi/epdf/10.1089/cmb.2022.0261'
url_code: 'https://github.com/algbio/flow-decomposition-safety'
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
