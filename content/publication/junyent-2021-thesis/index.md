---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Width-Based Planning and Learning
subtitle: ''
summary: ''
authors:
- Miquel Junyent
tags: []
categories: []
date: '2021-10-15'
lastmod: 2021-11-10T20:23:11+01:00
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
publishDate: '2021-11-10T19:23:11.195962Z'
publication_types:
- '7'
abstract: Optimal sequential decision making is a fundamental problem to many diverse fields. In recent years, Reinforcement Learning (RL) methods have experienced unprecedented success, largely enabled by the use of deep learning models, reaching human-level performance in several domains, such as the Atari video games or the ancient game of Go. In contrast to the RL approach in which the agent learns a policy from environment interaction samples, ignoring the structure of the problem, the planning approach for decision making assumes known models for the agent's goals and domain dynamics, and focuses on determining how the agent should behave to achieve its objectives. Current planners are able to solve problem instances involving huge state spaces by precisely exploiting the problem structure that is defined in the state-action model.

In this work we combine the two approaches, leveraging fast and compact policies from learning methods and the capacity to perform  lookaheads in combinatorial problems from planning methods. In particular, we focus on a family of planners called width-based planners, that has demonstrated great success in recent years due to its ability to scale independently of the size of the state space. The basic algorithm, Iterated Width (IW), was originally proposed for classical planning problems, where a model for state transitions and goals, represented by sets of atoms, is fully determined. Nevertheless, width-based planners do not require a fully defined model of the environment, and can be used with simulators. For instance, they have been recently applied in pixel domains such as the Atari games.

Despite its success, IW is purely exploratory, and does not leverage past reward information. Furthermore, it requires the state to be factored into features that need to be pre-defined for the particular task. Moreover, running the algorithm with a width larger than 1 in practice is usually computationally intractable, prohibiting IW from solving higher width problems.

We begin this dissertation by studying the complexity of width-based methods when the state space is defined by multivalued features, as in the RL setting, instead of Boolean atoms. We provide a tight upper bound on the amount of nodes expanded by IW, as well as overall algorithmic complexity results. In order to deal with more challenging problems (i.e., those with a width higher than 1), we present a hierarchical algorithm that plans at two levels of abstraction. A high-level planner uses abstract features that are incrementally discovered from low-level pruning decisions. We illustrate this algorithm in classical planning PDDL domains as well as in pixel-based simulator domains. In classical planning, we show how IW(1) at two levels of abstraction can solve problems of width 2.

To leverage past reward information, we extend width-based planning by incorporating an explicit policy in the action selection mechanism. Our method, called π-IW, interleaves width-based planning and policy learning using the state-actions visited by the planner. The policy estimate takes the form of a neural network and is in turn used to guide the planning step, thus reinforcing promising paths. Notably, the representation learned by the neural network can be used as a feature space for the width-based planner without degrading its performance, thus removing the requirement of pre-defined features for the planner. We compare π-IW with previous width-based methods and with AlphaZero, a method that also interleaves planning and learning, in simple environments, and show that π-IW has superior performance. We also show that the π-IW algorithm outperforms previous width-based methods in the pixel setting of Atari games suite. Finally, we show that the proposed hierarchical IW can be seamlessly integrated with our policy learning scheme, resulting in an algorithm that outperforms flat IW-based planners in Atari games with sparse rewards.

publication: 'PhD thesis Universitat Pompeu Fabra'
url_pdf: http://tiny.cc/thesis-Junyent
url_slides: http://tiny.cc/slides-thesis-Junyent
---
