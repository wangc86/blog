+++
title = "Safety Software Systems Design for Self-Driving Cars (2014-2015)"
date = 2018-06-02T17:31:34-05:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "A collaborative research effort with General Motors, Inc. and University of Pennsylvania, USA."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
In this project, we collaborated with both the [Real Time Systems Group](https://rtg.cis.upenn.edu) at the University of Pennsylvania and [General Motors](https://www.gm.com/). In particular, we studied safe software systems interaction for self-driving cars. Adaptive Cruise Control (ACC), for example, is a self-driving feature that maintains a safe distance to the leading car by managing the vehicle speed. Unintended interactions between self-driving features may occur, however, in situations such as driving on a curvy road. Changing vehicle speed may cause oversteering/understeering in the presence of another self-driving feature, called Lane-Keeping Control (LKC), which tries to steer the vehicle to make it stay in the current lane.

Fortunately, there are ways to identify such interactions (e.g., ACC vs. LKC) at the design time of the self-driving features. But since at run-time some identified interactions rarely happen (which is a good thing though), it may be an overkill if we build a system that aggressively guards those conditions (for example, by restricting the allowed vehicle speed every time both ACC and LKC are functioning). A way to improve the situation is to check those rare conditions at run-time and respond with verified consolidating strategies.
