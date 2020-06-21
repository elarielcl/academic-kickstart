
---
title: "Three Boxes"
summary: "A boxes' puzzle"
authors:
- admin
tags:
- Puzzle
date: 2019-09-21T02:00:00
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

In this puzzle we have $3$ boxes containing only <span style="color: green;">apples</span>, only <span style="color: orange;">oranges</span>, and <span style="color: green;">apples</span> and <span style="color: orange;">oranges</span> each.

The boxes are closed and labeled: <span style="color: green;">apples</span>, <span style="color: orange;">oranges</span>, and <span style="color: green;">apples</span> and <span style="color: orange;">oranges</span>, but we know for a fact that these labels are incorrect.

![threeBoxesLabeled](./threeBoxesLabeled.png)

Our task is to put the labels in the right boxes. We can ask for showing us one fruit from one box of our choose, but without showing us the entire content of this box.

What box should we choose? Why?

<details>
<summary>Solution</summary>
<div style="border-left: 6px solid; border-color: #2196F3; background-color: #ddffff; padding: 0.01em 1em;">
We choose the box labeled <span style="color: green;">apples</span> and <span style="color: orange;">oranges</span>. If we see and <span style="color: green;">apple</span> (other case is analogous), then the right label for this box is <span style="color: green;">apples</span> (as the label <span style="color: green;">apples</span> and <span style="color: orange;">oranges</span> is wrong and it couldn't be <span style="color: orange;">oranges</span>). Finally, as the <span style="color: orange;">oranges</span> label is incorrect we put it on the other box and put <span style="color: green;">apples</span> and <span style="color: orange;">oranges</span> on this box.
</div>
</details>
