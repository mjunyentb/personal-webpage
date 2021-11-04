---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: PhD Candidate
    company: Universitat Pompeu Fabra
    company_url: 'https://www.upf.edu/web/ai-ml'
    company_logo: 
    location: Barcelona, Spain
    date_start: '2016-10-03'
    date_end: '2021-10-02'
    description: >-
    * PhD thesis [Width-Based Planning and Learning](https://tiny.cc/thesis-Junyent), on the intersection of AI planning and deep reinforcement learning.
    * Successfully defended on October 15th 2021 with Excellent and ``Cum Laude'' mention.
    * My PhD thesis was about integrating width-based planning, a family of algorithms originally designed for classical/symbolic planning, with policy learning, similar to the famous AlphaZero algorithm (which I implemented and compared to), where the planning is guided by a policy and, in turn, the planner acts as a teacher to the policy estimate. In the thesis, I also explored the use of hierarchical planning as well as feature learning, and I had the opportunity to learn and implement deep reinforcement learning algorithms such as DQN, A3C, PPO or AlphaZero.
    * Teaching in BSc Computer Science:
         * Probabilistic Graphical Models - Seminars and labs (2019-20 and 2020-21),
         * Data Structures and Algorithms II - labs (2017-18 and 2018-19),
         * Bachelor thesis supervision (2019-20): "Deep Q-learning for Hard Exploration Problems",
         * Board member of BSc and MSc thesis (2018-19, 2019-20, and 2020-21).
    * The first three years of my PhD were done at Grupo Oesía, an IT consulting company, as part of the Industrial PhD program of the Catalan government. 

  - title: Summer Intern
    company: IRI - Institut de Robòtica i Informàtica Industrial (CSIC-UPC)
    company_url: 'https://www.iri.upc.edu/'
    company_logo: 
    location: Barcelona, Spain
    date_start: '2016-07-01'
    date_end: '2016-07-31'
    description: >-
      One-month internship where I worked on the adaptation of a learning-by-demonstration algorithm for a 7 DoF robot arm, testing it on simulation. It was implemented in Python, using ROS and Gazebo.
      
  - title: Project Engineer
    company: Center of Expertise in Computer Vision - NHL University of Applied Sciences
    company_url: 'https://www.cvds-nhlstenden.com/'
    company_logo: 
    location: Leeuwarden, The Netherlands
    date_start: '2014-08-28'
    date_end: '2015-08-31'
    description: >-
      As a project engineer, I supervised computer vision related projects while doing research on how to control an Unmanned Aerial Vehicle (UAV) with all computation and sensors on board. I also piloted UAVs indoors for autonomous flight tests, participated in trade shows and workshops, and taught a one week course in computer vision. 

  - title: Intern
    company: Center of Expertise in Computer Vision - NHL University of Applied Sciences
    company_url: 'https://www.cvds-nhlstenden.com/'
    company_logo: 
    location: Leeuwarden, The Netherlands
    date_start: '2014-02-01'
    date_end: '2014-07-31'
    description: >-
       Bachelor thesis: Autonomous flight of an hexacopter using onboard image processing. 

design:
  columns: '2'
---
