+++
title = "Scheduling Wireless Sensor Networks (2009-2010)"
date = 2018-06-02T17:30:13-05:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "Leveraging graph theory for low-latency and adaptive wireless transmissions."

# Optional image to display on homepage.
image_preview = "hidden-square.png"

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

[[gallery_item]]
album = "1"
image = "hidden-square.png"
caption = ""

[[gallery_item]]
album = "1"
image = "dcls-ijahuc.png"
caption = ""


+++
In scheduling TDMA-based wireless sensor networks, people often model the problem as certain type of [graph coloring](https://en.wikipedia.org/wiki/Graph_coloring). However, such an approach could under-utilize available bandwidth for transmission, because of a phenomenon we called *hidden square*: Consider coloring n-by-n squares. It may be possible to color each square with additional colors while still maintaining that no adjacent square will have same color. Applied to wireless scheduling, the above observation suggests that there may be some *hidden* time slot assignments opportunities, and with the additional slot assigned to wireless nodes one may reduce the delay for nodes to wait for next transmission.

This project has borne three fruits. (1) We studied the hidden square phenomenon and accordingly introduced *DCLS*, a distributed collision-free low-latency link scheduling for wireless sensor networks. The delay performance of DCLS is asymptotically smaller than that of conventional graph coloring. (2) We further analyzed the conventional unit disk graph model, and derived the upper bound of the maximum vertex degree on vertex insertion. Potential applications include efficient local rescheduling by slot stealing, useful for wireless networks subject to dynamic changes in node connectivity (e.g., due to node mobility, failure, or re-deployment). (3) The idea of local rescheduling then was further explored by [Dr. Chun-Hao Yang](https://dcl.ee.ncku.edu.tw/wordpress/?p=35) and [Dr. Kuo-Feng Ssu](https://dcl.ee.ncku.edu.tw/wordpress/?p=71), who introduced algorithms for wireless local rescheduling, along with experimental evaluation.

The first part of the contribution has been published in 2010, and the second and third parts have been published in 2018.

{{< gallery album="1" >}}
