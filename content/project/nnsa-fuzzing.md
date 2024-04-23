+++
title = "Using Fuzz Testing to Detect Software Tampering"
date = 2023-02-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["nuclear treaty assurance"]

# Project summary to display on homepage.
summary = "This project aims verify that software operating on arms control monitoring equipment is within agreed parameters.  It is funded by the National Nuclear Security Administration Office of Defense Nuclear Nonproliferation Research and Development and is led by [Sean Peisert](https://https://www.cs.ucdavis.edu/~peisert/)."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

featured = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


## Project Summary

It is essential to have the ability to verify that software operating on arms control monitoring equipment is within agreed parameters and has not undergone modification.  Existing approaches to ensuring the absence of tampering are outdated and are easily defeated by a motivated adversary.  Specifically, we use a coverage-guided, gray-box fuzzing approach to test the response of binaries to a wide range of inputs to increase confidence that the binary is behaving as expected. Our approach brings modern software analysis tools to bear to address today's challenges.  Success in our project would enable identification of a critical mass of alterations of a software’s logic that have the potential to affect the output of the nuclear monitoring software, and provide a different result to inspectors.


This project is supported by the [National Nuclear Security Administration
Office of Defense Nuclear Nonproliferation Research and Development](https://www.energy.gov/nnsa/nonproliferation).

#### Principal Investigators:
[Sean Peisert](https://https://www.cs.ucdavis.edu/~peisert/) (PI; LBNL) \
[Barton Miller](https://pages.cs.wisc.edu/~bart/) (Co-PI; University of Wisconsin-Madison)


#### Senior Personnel:

Joshua Boverhof (LBNL) \
Elisa Heymann Pignolo (University of Wisconsin-Madison) \
[Jayson Vavrek](https://scholar.google.com/citations?user=BhqfFmwAAAAJ&hl=en&oi=ao) (LBNL)


### Publications resulting from this project:

Jayson R. Vavrek, Luozhong Zhou, Joshua Boverhof, Elisa R. Heymann, Barton P. Miller, and Sean Peisert. [Differential Fuzz Testing to Detect Tampering In Sensor Systems and its Application to Arms Control Authentication](https://arxiv.org/abs/2404.05946), arXiv preprint 2404.05946, 9 Apr 2024.


More information is available on other Berkeley Lab R&D projects focusing on [cybersecurity](/projects/).
