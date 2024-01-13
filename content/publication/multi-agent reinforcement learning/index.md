---
title: 'TraCo: Learning Virtual Traffic Coordinator for Cooperation with Multi-Agent Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiwei Liu
  - Wei Jing
  - Lingping Gao
  - admin
  - Gang Xu
  - Yong Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-09-06T00:00:00Z'
doi: '10.15607/RSS.2023.XIX.101'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning*
publication_short: In *Conference on Robot Learning (coRL)*

abstract: Multi-agent reinforcement learning (MARL) has emerged as a popular technique in diverse domains due to its ability to automate system controller design and facilitate continuous intelligence learning. For instance, traffic flow is often trained with MARL to enable intelligent simulations for autonomous driving. However, The existing MARL algorithm only characterizes the relative degree of each agent’s contribution to the team, and cannot express the contribution that the team needs from the agent. Especially in the field of autonomous driving, the team changes over time, and the agent needs to act directly according to the needs of the team. To address these limitations, we propose an innovative method inspired by realistic traffic coordinators called the Traffic Coordinator Network (TraCo). Our approach leverages a combination of cross-attention and counterfactual advantage function, allowing us to extract distinctive characteristics of domain agents and accurately quantify the contribution that a team needs from an agent. Through experiments conducted on four traffic tasks, we demonstrate that our method outperforms existing approaches, yielding superior performance. Furthermore, our approach enables the emergence of rich and diverse social behaviors among vehicles within the traffic flow.

  
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Traffic Simulation, Autonomous Driving, Multi-agent Reinforcement Learning]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v229/liu23f/liu23f.pdf'
#url_code: 'https://github.com/Kguo-cs/ccil'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://openreview.net/attachment?id=TgJ8vJUVUBR&name=poster_spotlight_video'

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
