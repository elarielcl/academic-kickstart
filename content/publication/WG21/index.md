---
title: "A linear-time parameterized algorithm for computing the width of a DAG"
authors:
- admin
- Massimo Cairo
- Brendan Mumey
- Romeo Rizzi
- Alexandru I. Tomescu
date: "2021-08-01T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-86838-3_20"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In International Workshop on Graph-Theoretic Concepts in Computer Science, *WG 2021*
publication_short: In *WG 2021*

abstract:  "The width k of a directed acyclic graph (DAG) G = (V, E) equals the largest number of pair-wise non-reachable vertices. Computing the width dates back to Dilworth's and Fulkerson's results in the 1950s, and is doable in quadratic time in the worst case. Since k can be small in practical applications, research has also studied algorithms whose complexity is parameterized on k. Despite these efforts, it is still open whether there exists a linear-time O(f(k)(|E| + |V|)) parameterized algorithm computing the width. We answer this question affirmatively by presenting an O(k2^k|E| + k^24^k|V|)-time algorithm, based on a new notion of frontier antichains. As we process the vertices in a topological order, all the frontier antichains can be maintained with the help of several combinatorial properties, paying only f(k) along the way. The fact that the width can be computed by a single f(k)-sweep of the DAG is a new surprising insight into this classical problem. Our algorithm also allows deciding whether the DAG has width at most w in time O(f(min(w,k))(|E|+|V|))."

# Summary. An optional shortened abstract.
summary: "We describe an parameterized algorithm to compute the width k of a DAG in time O(k2^k|E| + k^24^k|V|)."


tags:
- Conference Publication
- WG
featured: true

links: []
url_pdf: 'https://arxiv.org/pdf/2007.07575.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'files/wg2021.pdf'
url_source: ''
url_video: 'files/wg2021.mp4'
url_doi: 'https://doi.org/10.1007/978-3-030-86838-3_20'

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
