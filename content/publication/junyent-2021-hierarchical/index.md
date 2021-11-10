---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hierarchical Width-Based Planning and Learning
subtitle: ''
summary: ''
authors:
- Miquel Junyent
- Vicenç Gómez
- Anders Jonsson
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-11-03T11:39:30+01:00
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
publishDate: '2021-11-03T10:39:30.547365Z'
publication_types:
- '1'
abstract: Width-based search methods have demonstrated state-of-the-art performance
  in a wide range of testbeds, from classical planning problems to image-based simulators
  such as Atari games. These methods scale independently of the size of the state-space,
  but exponentially in the problem width. In practice, running the algorithm with
  a width larger than 1 is computationally intractable, prohibiting IW from solving
  higher width problems. In this paper, we present a hierarchical algorithm that plans
  at two levels of abstraction. A high-level planner uses abstract features that are
  incrementally discovered from low-level pruning decisions. We illustrate this algorithm
  in classical planning PDDL domains as well as in pixel-based simulator domains.
  In classical planning, we show how IW(1) at two levels of abstraction can solve
  problems of width 2. For pixel-based domains, we show how in combination with a
  learned policy and a learned value function, the proposed hierarchical IW can outperform
  current flat IW-based planners in Atari games with sparse rewards.
publication: '*Proceedings of the International Conference on Automated Planning and
  Scheduling*'
url_pdf: https://arxiv.org/pdf/2101.06177.pdf
url_poster: https://icaps21.icaps-conference.org/link/posters/index.html?id=322
url_slides: https://docs.google.com/presentation/d/e/2PACX-1vRa4_UiD3DcW5oUQ9ITBxPf89P__Mq1ibzxNfEgOpPjG-ZKQ26B35p-oNxlbgLiTB9cNh_zAl5FGfhX/pub?start=true&loop=false&delayms=3000
url_video: https://icaps21.icaps-conference.org/exhibition/index.html?channel=322
url_code: https://github.com/aig-upf/hierarchical-IW
---
