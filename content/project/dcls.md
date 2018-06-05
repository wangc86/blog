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

[[gallery_item]]
album = "1"
image = "dcls-msthesis.png"
caption = ""

+++
In order to guarantee collision-free transmissions in TDMA-based wireless sensor networks, a substantial amount of work in literature has been done by modeling the problem into the minimum graph coloring. However, such approach is not effective towards low-latency transmissions due to a phenomenon we called *hidden square*: Consider coloring n-by-n squares. It is possible to color each square with multiple colors while still satisifying the constraint that no adjacent square can have same color. Applied to wireless scheduling,
these additional color assignments, now associated with the time slot assignments, can reduce the data buffering delay.

This project has borne three research fruits. (1) We studied the hidden square phenomenon and accordingly introduced *DCLS*, a distributed collision-free low-latency link scheduling for wireless sensor networks. With DCLS, the delay is asymptotically smaller than that with the conventional graph coloring model. (2) We further explored properties in the unit disk graph model, and derived the upper bound of the maximum vertex degree on vertex insertion. Potential applications include rescheduling wireless sensor networks, mobile ad hoc networks, and wireless networks with mobile stations. In those cases, local rescheduling may be needed upon change in the connectivity between wireless nodes. (3) The idea of local rescheduling was later on significantly extended by [Dr. Chun-Hao Yang](https://dcl.ee.ncku.edu.tw/wordpress/?p=35) and [Dr. Kuo-Feng Ssu](https://dcl.ee.ncku.edu.tw/wordpress/?p=71). The result included both local rescheduling algorithms and experimental evaluation.

The first part of the contribution has been published in 2010, and the second and third parts have been published in 2018.

{{< gallery album="1" >}}
