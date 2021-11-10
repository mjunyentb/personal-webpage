---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Deep Policies for Width-Based Planning in Pixel Domains
subtitle: ''
summary: ''
authors:
- Miquel Junyent
- Anders Jonsson
- Vicenç Gómez
tags: []
categories: []
date: '2019-01-01'
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
publishDate: '2021-11-03T10:39:30.395725Z'
publication_types:
- '1'
abstract: Width-based planning has demonstrated great success in recent years due
  to its ability to scale independently of the size of the state space. For example,
  Bandres et al. (2018) introduced a rollout version of the Iterated Width algorithm
  whose performance compares well with humans and learning methods in the pixel setting
  of the Atari games suite. In this setting, planning is done on-line using the \"screen\"
  states and selecting actions by looking ahead into the future. However, this algorithm
  is purely exploratory and does not leverage past reward information. Furthermore,
  it requires the state to be factored into features that need to be pre-defined for
  the particular task, e.g., the B-PROST pixel features. In this work, we extend width-based
  planning by incorporating an explicit policy in the action selection mechanism.
  Our method, called π-IW, interleaves width-based planning and policy learning using
  the state-actions visited by the planner. The policy estimate takes the form of
  a neural network and is in turn used to guide the planning step, thus reinforcing
  promising paths. Surprisingly, we observe that the representation learned by the
  neural network can be used as a feature space for the width-based planner without
  degrading its performance, thus removing the requirement of pre-defined features
  for the planner. We compare π-IW with previous width-based methods and with AlphaZero,
  a method that also interleaves planning and learning, in simple environments, and
  show that π-IW has superior performance. We also show that π-IW algorithm outperforms
  previous width-based methods in the pixel setting of Atari games suite.
publication: '*Proceedings of the Twenty-Ninth International Conference on Automated
  Planning and Scheduling (ICAPS 2019)*'
url_pdf: https://arxiv.org/pdf/1904.07091.pdf
url_poster: https://drive.google.com/file/d/1VGfyGOoyc5VJ9HS-h8Jeds_9UL4zy6jh/view?usp=sharing
url_slides: https://docs.google.com/presentation/d/e/2PACX-1vRBB_HFOV99SxtsfZCEvNo_02P29UDqmWL-qu9w5fQ8Du9eTHV5yeStz6GGUuinIQ/pub?start=true&loop=false&delayms=3000
url_code: https://github.com/aig-upf/pi-IW
---
