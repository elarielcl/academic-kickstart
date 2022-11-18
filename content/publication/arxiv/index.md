---
title: "Minimum Path Cover in Parameterized Linear Time"
authors:
- admin
- Massimo Cairo
- Brendan Mumey
- Romeo Rizzi
- Alexandru I. Tomescu
date: "2022-11-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arXiv
publication_short: In arXiv

abstract:  "A *minimum path cover* (MPC) of a directed acyclic graph (DAG) $G = (V,E)$ is a minimum-size set of paths that together cover all the vertices of the DAG. Computing an MPC is a basic polynomial problem, dating back to Dilworth's and Fulkerson's results in the 1950s. Since the size $k$ of an MPC (also known as the *width*) can be small in practical applications, research has also studied algorithms whose running time is parameterized on $k$. We obtain a new MPC parameterized algorithm for DAGs running in time $O(k^2|V| + |E|)$. Our algorithm is the first solving the problem in parameterized linear time. Additionally, we obtain an edge sparsification algorithm preserving the width of a DAG but reducing $|E|$ to less than $2|V|$. This algorithm runs in time $O(k^2|V|)$ and requires an MPC of a DAG as input, thus its total running time is the same as the running time of our MPC algorithm."

# Summary. An optional shortened abstract.
summary: " We obtain a new MPC parameterized algorithm for DAGs running in time $O(k^2|V| + |E|)$. Our algorithm is the first solving the problem in parameterized linear time. Additionally, we obtain an edge sparsification algorithm preserving the width of a DAG but reducing $|E|$ to less than $2|V|$. This algorithm runs in time $O(k^2|V|)$ and requires an MPC of a DAG as input, thus its total running time is the same as the running time of our MPC algorithm."


tags:
- Preprint
- arXiv
featured: true

links: []
url_pdf: 'https://arxiv.org/pdf/2211.09659.pdf'
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
  caption: 'Back links point to antichain vertices in the same path'
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
