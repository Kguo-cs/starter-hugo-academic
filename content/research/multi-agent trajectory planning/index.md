---
title: Decentralized Collision Avoidance
summary: Navigating multiple agents to their goals without mutual communication and collisions. 
tags:
  - Rule-based
  - Trajectory planning
date: '2021-03-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Circle scenario
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_pdf: 'https://ieeexplore.ieee.org/document/9384148'
url_code: 'https://github.com/Kguo-cs/vr-orca'
url_video: 'https://sites.google.com/view/vrorca'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

---

As one of the most popular multi-agent path planning approaches, the optimal reciprocal collision avoidance (ORCA) algorithm assumes that each agent takes half the responsibility for collision avoidance. However, due to the asymmetric situation faced by adjacent agents, they are expected to take different responsibilities for collision avoidance to improve the entire crowd's navigation performance. Thus, in this letter, we propose the variable responsibility optimal reciprocal collision avoidance (VR-ORCA) algorithm, which relaxes the original assumption in ORCA and only requires the responsibilities of a pair of agents sum to one. In particular, the responsibility division between a pair of nearby agents is determined independently for each agent by minimizing a cost function involving their common neighbors. We validate our approach on a variety of simulated benchmarks and the results demonstrate that our novel method is beneficial in reducing the collision probability, travel time and distance of ORCA.
  
