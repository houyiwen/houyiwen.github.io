---
title: 'Effective Offline Robot Learning with Structured Task Graph'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jinming Ma
  - Haoyuan Sun
  - Feng Wu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-04-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Robotics and Automation Letters
publication_short: RA-L

abstract: Offline reinforcement learning (RL) has shown great potential in many robotic tasks, where doing trial-and-error with the environment is risky, costly, or time-consuming. However, it is still hard to succeed in long-horizon tasks especially when given suboptimal and multimodal offline datasets. Nevertheless, existing RL methods rarely consider the structured information in offline datasets, which are commonly found in many robotic tasks. To address these challenges, we propose a novel offline RL approach that combines the techniques of dataset augmentation and subtask relabeling. Specifically, we first extract the subtasks and build the task graph based on the structured information in offline datasets. We then use the task graph to sample and generate an augmented dataset, which is more suitable for offline RL learning. After that, we relabel the dataset according to the task graph and finally learn a subtask-conditioned policy to complete the task. By doing so, we decompose the task of reaching a long-horizon goal state into a sequence of easier subtasks. This is not only useful for handling the long-horizon problem, but also reduces the error introduced by the offline dataset. We conducted extensive experiments in both the D4RL benchmark dataset and real-world robot with complex manipulation tasks. The experimental results show that our method significantly advances the state-of-the-art baselines in most tasks, particularly in long-horizon manipulation tasks with limited human demonstrations.

# Summary. An optional shortened abstract.
summary: "IEEE Robotics and Automation Letters (RA-L), 2024"


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10400863'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/o-oFSCBaR24'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview'
  focal_point: ''
  preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
