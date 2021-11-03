---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving width-based planning with compact policies
subtitle: ''
summary: ''
authors:
- Miquel Junyent
- Anders Jonsson
- Vicenç Gómez
tags: []
categories: []
date: '2018-01-01'
lastmod: 2021-11-03T12:27:08+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-11-03T11:27:08.404945Z'
publication_types:
- '1'
abstract: Optimal action selection in decision problems characterized by sparse, delayed
  rewards is still an open challenge. For these problems, current deep reinforcement
  learning methods require enormous amounts of data to learn controllers that reach
  human-level performance. In this work, we propose a method that interleaves planning
  and learning to address this issue. The planning step hinges on the Iterated-Width
  (IW) planner, a state of the art planner that makes explicit use of the state representation
  to perform structured exploration. IW is able to scale up to problems independently
  of the size of the state space. From the state-actions visited by IW, the learning
  step estimates a compact policy, which in turn is used to guide the planning step.
  The type of exploration used by our method is radically different than the standard
  random exploration used in RL. We evaluate our method in simple problems where we
  show it to have superior performance than the state-of-the-art reinforcement learning
  algorithms A2C and Alpha Zero. Finally, we present preliminary results in a subset
  of the Atari games suite.
publication: '*ICML / IJCAI / AAMAS Workshop on Planning and Learning*'
url_pdf: https://arxiv.org/pdf/1806.05898.pdf
---
