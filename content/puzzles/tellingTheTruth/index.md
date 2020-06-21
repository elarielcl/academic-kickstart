---
title: "Who's telling the truth?"
summary: "Let's caputure the liar/s"
authors:
- admin
tags:
- Puzzle
date: 2019-09-30T02:00:00
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

In this puzzle we have $32$ people. Some of these always tell the truth and the rest always lie. Our task here is to find out the liar/s. For these, every person writes down each of these sentences:

> Exactly one of these $32$ people is a liar

<span/>

> Exactly two of these $32$ people are liars

...

> Exactly thirty two of these $32$ people are liars


Who is/are the liar/s? Why?

<details>
<summary>Solution</summary>
<div style="border-left: 6px solid; border-color: #2196F3; background-color: #ddffff; padding: 0.01em 1em;">
First, it is not possible that two (or more) people are telling the truth, because in that case we have that exactly $i$ and $j$ people are liars, which is not possible. Second, is not possible that everyone is a liar, because in that case everybody is telling the truth and then there are $i$ liars which is not possible. Finally, the only person telling the truth is the one saying "Exactly thirty one of these $32$ people are lying", which are the rest of the people.
</div>
</details>
