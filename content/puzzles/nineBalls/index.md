---
title: "Nine Balls"
summary: "A balls' puzzle"
authors:
- admin
tags:
- Puzzle
date: 2019-09-21T22:00:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 1
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
math : true
---

In this puzzle we have $9$ identical balls, except by one, which weighs less. Our task is to identify the light ball, and for this we have a scale in which we can compare the weight of $2$ sets of balls.

![scale](./scale.png)

How do we ensure the least number of scale comparisons? What is this number?

<details>
<summary>Solution</summary>
<div style="border-left: 6px solid; border-color: #2196F3; background-color: #ddffff; padding: 0.01em 1em;">
We can ensure only $2$ comparisons as follows. First, compare the weight of two set of $3$ balls: if the scale is balanced, then the light ball is among the $3$ balls not in the scale; if the scale is unbalanced, then the light ball is in the lighter weighed set of balls. Note that in any case the problem is reduced to solve the same problem but with $3$ balls, which can be solved with just $1$ comparison as before: Compare $2$ balls: if the scale is balanced the light ball is the other one, otherwise the light ball is the lighter in the comparison.
</div>
</details>

