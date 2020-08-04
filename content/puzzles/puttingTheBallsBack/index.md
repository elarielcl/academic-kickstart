---
title: "Putting the balls back!"
summary: "Another balls' puzzle"
authors:
- admin
tags:
- Puzzle
date: 2020-08-04T18:00:00
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

In this puzzle we are presented with a maze and $5$ balls of different colors (<span style="color: #ff0000;">red</span>, <span style="color: #00ff00ff;">green</span>, <span style="color: #b400ff;">violet</span>, <span style="color: #ffff00;">yellow</span> and <span style="color: #0000ff;">blue</span>), which are placed in $5$ different holes. In total there are $6$ holes also colored in different colors (<span style="color: #ffff00;">yellow</span>, <span style="color: #0000ff;">blue</span>, <span style="color: #b400ff;">violet</span>, <span style="color: #ff0000;">red</span>, <span style="color: #00ff00ff;">green</span> and <span style="color: #000000;">black</span>).

Two holes can be connected, meaning that we can move ball between the respective holes. Specifically, we are allowed to move a ball into an empty hole if this is connected to the hole containing the ball.

In the following animation we can see a movement of the <span style="color: #00ff00ff;">green</span> ball to the <span style="color: #000000;">black</span> hole, and then a movement of the <span style="color: #0000ff;">blue</span> ball to its <span style="color: #0000ff;">blue</span> hole.

<img src="./movements.gif" alt="graph" width="500"/>

Just as a convention we will name a movement after the hole it leaves empty. So the previous animation shows the movements <span style="color: #0000ff;">blue</span> and <span style="color: #00ff00ff;">green</span>.

To solve this puzzle we must move the balls so we end up with every ball on its respective hole, that is, the following configuration:

<img src="./50.svg" alt="graph" width="500"/>

What are the movements to reach this state?

<details>
<summary>Solution</summary>
<div style="border-left: 6px solid; border-color: #2196F3; background-color: #ddffff; padding: 0.01em 1em;">
<img src="./solution.gif" alt="graph" width="500"/>
... More explanation soon ...
</div>
</details>
