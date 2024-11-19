---
title: Virtual Seminar Prof. Andrea Del Prete

event: Seminar "Globally Optimal and Safe Robot Control"
event_url: https://docs.google.com/document/d/1ZHZ0zE2q8QiXXyLHZETxacUszOmrpWBfUZXTWs3IAHs/edit?tab=t.0

location: Virtual
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: First seminar of the 2024/2025 virtual seminar series of the IEEE RAS TC on Model-based Optimization for Robotics.
# abstract: We are thrilled to announce our participation in the **I-RIM 3D 2024** conference. Our team has several exciting activities planned!

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-05'
# date_end: '2024-12-05'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-11-19T00:00:00Z'

authors: [andreadelprete]
tags: []
profile: false

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
research: []
---

## Upcoming Seminar

**Organizers**: [IEEE RAS TC on Model-based Optimization for Robotics](https://www.tcoptrob.org/)

**Speaker**: [Andrea Del Prete](/author/andrea-del-prete/)

**Title**: Globally Optimal and Safe Robot Control

**Abstract**: In recent years, advanced data-driven control methods are unlocking the potential of complex robotics systems, and we can expect this trend to continue at an exponential rate in the near future. However, these methods present two major shortcomings. First, their training process is excessively data hungry and strongly dependent on the exploration strategy. Second, the resulting policies cannot ensure constraint satisfaction (i.e. safety). In this talk I will discuss how we are using tools from optimal control to address these two issues.

First, I will present "Continuous Actor Critic with Trajectory Optimization" (CACTO), a novel algorithm that combines Trajectory Optimization (TO) and Reinforcement Learning (RL). CACTO learns a control policy via TO-guided RL policy search. Our method is validated on several non-convex problems with different robotic systems. Our results show the great capabilities of CACTO in escaping local minima, while being more sample-efficient than DDPG and PPO. To address the issue of safety, a well-known tool is the control-invariant set (a.k.a. safe set). Unfortunately, for nonlinear systems, such sets can only be approximated. I will present some novel MPC schemes that guarantee safety under weaker assumptions than classic methods. Our key idea is to make the safe-set constraint move backward (i.e. recede) over the horizon. We evaluated our approaches on simulated robot manipulators, empirically demonstrating that they lead to less constraint violations, while retaining good tracking cost and computation times.

**Date**: Thursday, December 5th 2024

**Time**: 09:00-10:00 AM EST

**Link**: [here](https://columbiauniversity.zoom.us/j/91247893326?pwd=L2JWU21aQzc4cU1ZQklEb0QrWGQvdz09)