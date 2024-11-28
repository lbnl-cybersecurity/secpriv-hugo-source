+++
title = "Detecting Distributed Denial of Service Attacks on Wide-Area Networks"
date = 2017-03-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["network","machine learning","research cyberinfrastructure"]

# Project summary to display on homepage.
summary = "This project develops techniques for detecting DDoS attacks and disambiguating them from large-scale science flows.  It is funded by the DOE iJC3 Cyber research program and is led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/)."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


#### Principal Investigator:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI)

#### Faculty Scientists

[Chen-Nee Chuah](https://crd.lbl.gov/divisions/scidata/idf/affiliates/chen-nee-chuah/) (LBNL Faculty Scientist / UC Davis)  
[Dipak Ghosal](https://crd.lbl.gov/divisions/scidata/idf/affiliates/dipak-ghosal/) (LBNL Faculty Scientist / UC Davis)


#### Graduate Students

[Ross Gegan](https://crd.lbl.gov/divisions/scidata/idf/affiliates/ross-gegan/) (LBNL GSR / UC Davis)  \
[Chang Liu](https://crd.lbl.gov/divisions/scidata/idf/affiliates/chang-liu/) (LBNL GSR / UC Davis)


A large scale distributed denial of service (DDoS) attack has the potential to not only impact the target site, but impact performance along the entire network path. Today, DDoS mitigation across DOE Sites is largely handled at the site borders using a combination of heuristic and filtering techniques, manual changes, and commercial services that can "absorb" attacks against specific sites. With the scale of DDoS increasing dramatically with little indication of slowing down, the task of DDoS detection and mitigation across ESnet’s extensive wide area network (WAN) becomes a higher priority, with increased complexity of detection and execution.

As ESnet pushes the boundary of modern network technology, we must also develop the security tools and strategies that are most effective for monitoring the WAN to prevent DDoS attacks for a next-generation network architecture. Specifically, this includes research issues of disambiguating very large science flows from malicious attacks, and developing mechanisms and tools for DDoS detection that can integrate this knowledge.

While commercial DDoS tools and services exist to mitigate DDoS attacks to certain extents, and within typical enterprise and service provider networks, the effectiveness of those tools is extremely limited. ESnet transits all types of traffic, from ordinary websites and email to massive scientific data sets, thus DDoS protection targeting multiple facets of the network stack is required. Since commercial tools are typically and almost exclusively focused on commercial enterprise traffic, research on both detecting and mitigating DDoS is still deemed as essential as demonstrated by the interest of numerous other organizations funding research efforts in this space, including NSF, DARPA's "Extreme DDoS Defense (XD3)," and others. However, most research \[BBHkc09,MR04\] and commercial service products target protection for individual sites, not entire WANs, let alone WANs carrying large volumes of scientific traffic. Since it is ESnet's responsibility to protect availability for the entire ESnet WAN, this raises both the importance and value of blocking attacks earlier, before they reach individual DOE Sites.

A focus in the DOE space is ESnet’s ability to inform DDoS identification techniques with additional information sources to reduce the likelihood of false positives. WAN level detection algorithms can be bolstered by information provided by DDoS detection information provided by the Sites to confirm positive DDoS detection. On the opposite front, pre-defined network circuit reservations (as are available through OSCARS) can help identify a large flow as being scientific data rather than a malicious attack. The DOE is in a unique position to perform the research necessary to take a very different approach from both commercial services as well as the research approaches pursued by funding agencies other than DOE.

This project is supported by the US Department of Energy's  [iJC3](https://energy.gov/articles/secretary-monizs-testimony-senate-committee-energy-natural-resources-field-hearing-seattle) [Cyber research](http://ijc3.lbl.gov/) program

[DDoS Detection Source Code at GitHub](https://github.com/lbnl-cybersecurity/ddos-detection)

### Publications resulting from this project:

Chang Liu, "Network Monitoring and Security Enhancement in Software-Defined Networking," Ph.D Dissertation, University of California, Davis, Department of Electrical and Computer Engineering, May 2019.  (Advisor: Prof. Chen-Nee Chuah.)

### Software resulting from this project:

[LBNL DDoS Detection on Science Networks](https://github.com/lbnl-cybersecurity/ddos-detection)


More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for research cyberinfrastructure and high-performance computing](/research/research-cyberinfrastructure/).
