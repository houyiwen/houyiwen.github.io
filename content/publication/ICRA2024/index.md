---
title: 'Improving Offline Reinforcement Learning with Inaccurate Simulators'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Haoyuan Sun
  - Jinming Ma
  - Feng Wu

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-04-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Robotics and Automation (ICRA)
publication_short: ICRA

abstract: Offline reinforcement learning (RL) provides a promising approach to avoid costly online interaction with the real environment. However, the performance of offline RL highly depends on the quality of the datasets, which may cause extrapolation error in the learning process. In many robotic applications, an inaccurate simulator is often available. However, the data directly collected from the inaccurate simulator cannot be directly used in offline RL due to the well-known exploration-exploitation dilemma and the dynamic gap between inaccurate simulation and the real environment. To address these issues, we propose a novel approach to combine the offline dataset and the inaccurate simulation data in a better manner. Specifically, we pre-train a generative adversarial network (GAN) model to fit the state distribution of the offline dataset. Given this, we collect data from the inaccurate simulator starting from the distribution provided by the generator and reweight the simulated data using the discriminator. Our experimental results in the D4RL benchmark and a real-world manipulation task confirm that our method can benefit more from both inaccurate simulator and limited offline datasets to achieve better performance than the state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: "IEEE International Conference on Robotics and Automation (ICRA), 2024. (accepted)"

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: uploads/ICRA24_3892_MS.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: uploads/ICRA24_3892_Presentation_Video.mp4

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
