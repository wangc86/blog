+++
title = "Cyber-Physical Event Processing Middleware (CPEP) (2015-2018)"
date = 2019-01-27
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "Enforcing both application-specific latency requirement and event's temporal validity."

# Optional image to display on homepage.
image_preview = "eventProcessors.png"

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
image = "cpep.png"
caption = ""

[[gallery_item]]
album = "1"
image = "eventProcessors.png"
caption = ""


+++
Cyber-physical systems (CPS) involve tight integration of cyber (computation) and physical domains, and both the effectiveness and correctness of a CPS application may rely on successful enforcement of constraints such as bounded latency and temporal validity subject to physical conditions. For many such systems (e.g., edge computing in the Industrial Internet of Things), it is desirable to enforce such constraints within a common middleware service (e.g., during event processing). In this project, we introduce *CPEP*, a new real-time middleware for cyber-physical event processing, with

1. extensible support for complex event processing operations
2. execution prioritization and sharing
3. enforcement of time consistency with load shedding
4. efficient memory management and concurrent data processing

We present the design, implementation, and empirical evaluation of CPEP and show that it can

1. support complex operations needed by many applications
2. schedule data processing according to consumers' priority levels
3. enforce temporal validity
4. reduce processing delay and improve throughput of time-consistent events.

We have implemented CPEP within the [TAO real-time event service](http://www.dre.vanderbilt.edu/~schmidt/TAO.html).

{{< gallery album="1" >}}


