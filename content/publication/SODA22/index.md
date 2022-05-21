---
title: "Sparsifying, Shrinking and Splicing for Minimum Path Cover in Parameterized Linear Time"
authors:
- admin
- Massimo Cairo
- Brendan Mumey
- Romeo Rizzi
- Alexandru I. Tomescu
date: "2022-01-09T00:00:00Z"
doi: "https://doi.org/10.1137/1.9781611977073.18"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In ACM-SIAM Symposium on Discrete Algorithms (SODA 2022)
publication_short: In SODA 2022

abstract:  "A minimum path cover (MPC) of a directed acyclic graph (DAG) $G = (V,E)$ is a minimum-size set of paths that together cover all the vertices of the DAG. Computing an MPC is a basic polynomial problem, dating back to Dilworth's and Fulkerson's results in the 1950s. Since the size $k$ of an MPC (also known as the width) can be small in practical applications, research has also studied algorithms whose complexity is parameterized on $k$. We obtain two new MPC parameterized algorithms for DAGs running in time $O(k^2|V|\\log(|V|) + |E|)$ and $O(k^3|V| + |E|)$. We also obtain a parallel algorithm running in $O(k^2|V| + |E|)$ parallel steps and using $O(\\log(|V|))$ processors (in the PRAM model). Our latter two algorithms are the first solving the problem in parameterized linear time. Finally, we present an algorithm running in time $O(k^2|V|)$ for transforming any MPC to another MPC using less than $2|V|$ distinct edges, which we prove to be asymptotically tight. As such, we also obtain edge sparsification algorithms preserving the width of the DAG with the same running time as our MPC algorithms. At the core of all our algorithms we interleave the usage of three techniques: transitive sparsification, shrinking of a path cover, and the splicing of a set of paths along a given path."

# Summary. An optional shortened abstract.
summary: "We obtain two new MPC parameterized algorithms for DAGs running in time $O(k^2|V|\\log(|V|) + |E|)$ and $O(k^3|V| + |E|)$. We also obtain a parallel algorithm running in $O(k^2|V| + |E|)$ parallel steps and using $O(\\log(|V|))$ processors (in the PRAM model). We also obtain edge sparsification algorithms preserving the width of the DAG with the same running time as our MPC algorithms."


tags:
- Conference Publication
- SODA
featured: true

links: []
url_pdf: 'https://epubs.siam.org/doi/pdf/10.1137/1.9781611977073.18'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/soda2022.pdf'
url_source: ''
url_video: ''
url_doi: 'https://doi.org/10.1137/1.9781611977073.18'

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
