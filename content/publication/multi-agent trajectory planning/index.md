---
title: 'VR-ORCA: Variable Responsibility Optimal Reciprocal Collision Avoidance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dawei Wang
  - Tingxiang Fan
  - Jia Pan

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-03-23T00:00:00Z'
doi: '10.1109/LRA.2021.3067851'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-03-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE Robotics and Automation Letters (RAL)*

abstract: As one of the most popular multi-agent path planning approaches, the optimal reciprocal collision avoidance (ORCA) algorithm assumes that each agent takes half the responsibility for collision avoidance. However, due to the asymmetric situation faced by adjacent agents, they are expected to take different responsibilities for collision avoidance to improve the entire crowd's navigation performance. Thus, in this letter, we propose the variable responsibility optimal reciprocal collision avoidance (VR-ORCA) algorithm, which relaxes the original assumption in ORCA and only requires the responsibilities of a pair of agents sum to one. In particular, the responsibility division between a pair of nearby agents is determined independently for each agent by minimizing a cost function involving their common neighbors. We validate our approach on a variety of simulated benchmarks and the results demonstrate that our novel method is beneficial in reducing the collision probability, travel time and distance of ORCA.
  
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Multi-agent Trajectory Planning, Collision Avoidance]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9384148'
url_code: 'https://github.com/Kguo-cs/vr-orca'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://sites.google.com/view/vrorca'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
