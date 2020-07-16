---
title: "On the parameterized complexity of the Minimum Path Cover problem in DAGs"
authors:
- admin
- Massimo Cairo
- Brendan Mumey
- Romeo Rizzi
- Alexandru I. Tomescu
date: "2020-07-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arXiv
publication_short: In arXiv

abstract:  "A *minimum path cover* (MPC) of a directed acyclic graph (DAG) $G = (V,E)$ is a minimum-size set of paths that together cover all the vertices of the DAG. The size $k$ of a MPC is also called the *width* of $G$. Computing a MPC is a basic problem, dating back to Dilworth's and Fulkerson's results in the 1950s, and is solvable in quadratic time in the worst case. Since the width of the DAG can be small in practical applications (e.g.,~from bioinformatics), research has also studied algorithms whose complexity is parameterized on $k$. Despite these efforts, it is a major open problem whether there exists a *linear-time* $O(f(k)(|E| + |V|))$ parameterized algorithm. We present here two significant results in this direction.\n\nFirst, we obtain an $O(|E| + k^2|V|\\log{|V|})$-time algorithm, which in particular is faster than all existing MPC algorithms when $k = o(\\sqrt{|V|}/\\log{|V|})$ and $|E| = \\omega(k|V|)$ but $|E| = o(|V|^2)$. We obtain this by a new combination of three techniques: transitive edge sparsification (reducing the factor $O(|E|)$ to $O(k|V|)$), divide-and-conquer (enabling the use of sparsification), and shrinking (allowing to reuse and combine recursive solutions). This algorithm is also simple and can be parallelized, making it ideal for practical use. We also show that some basic problems on DAGs (reachability queries, longest increasing / common subsequence, co-linear chaining) get faster algorithms as immediate corollaries of this result.\n\n Second, we obtain an $O(poly(k)(2^k|E| + 4^k|V|))$-time algorithm for the dual problem of computing the width of the DAG. This is based on the notion of *frontier antichains*, generalizing the standard notion of right-most maximum antichain. As we process the vertices in a topological order, these (at most $2^k$) frontier antichains can be maintained with the help of several combinatorial properties. As such, it is enough to sweep the graph once from left to right, paying only $f(k)$ along the way, which is a new surprising insight into the classical MPC problem."

# Summary. An optional shortened abstract.
summary: "We describe indexes for searching large data sets for variable-length-gapped (VLG) patterns. Our best approach provides search speeds several times faster than prior art across a broad range of patterns and texts."


tags:
- Preprint
- arXiv
featured: true

links: []
url_pdf: ''
url_code: ''
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
