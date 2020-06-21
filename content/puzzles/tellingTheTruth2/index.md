---
title: "Who's telling the truth? (Part 2)"
summary: "Let's caputure the liar/s again"
authors:
- admin
tags:
- Puzzle
date: 2019-10-01T00:00:00
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

Now we have $64$ people. Again, some of these always tell the truth and the rest always lie. Our task here is to find out the liar/s. Every person writes down each of these sentences:

> At least one of these $64$ people is a liar

<span/>

> At least two of these $64$ people are liars

...

> At least sixty four of these $64$ people are liars


Who is/are the liar/s? Why?

<details>
<summary>Solution</summary>
<div style="border-left: 6px solid; border-color: #2196F3; background-color: #ddffff; padding: 0.01em 1em;">
First, we'll show that the last thirty two people are lying. By induction, suposse
that the last i people are lying, and by contradiction suposse that the $(i+1)$th $\le 32$
is telling the truth, then at least $64-i > 32$ are lying, and as we know that $i$ are lying,
then $> 32-i > 0$ of the rest are lying, that is at least one of the rest is lying, but in that case $< 63-i$ are lying which is a contradiction. Finally, note that the first $32$ people are telling the truth as the last $32$ are lying, and that they can't be lying because this would imply that less than $i \le 32$ are lying which is a contradiction with the current $\ge 33$ liars.
</div>
</details>
