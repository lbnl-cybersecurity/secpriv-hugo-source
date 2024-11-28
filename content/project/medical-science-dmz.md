+++
title = "Medical Science DMZ"
date = 2018-03-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["network","medical","research cyberinfrastructure"]

# Project summary to display on homepage.
summary = "We have defined a Medical Science DMZ as a method that allows data flows at scale while simultaneously addressing the HIPAA Security Rule and related regulations governing biomedical data and appropriately managing risk."

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

A [Science DMZ](https://fasterdata.es.net/science-dmz/) is a portion of the network, built at or near the local network perimeter of an individual research institution, that is designed such that the equipment, configuration, and security poli- cies are optimized for high-performance workflows and large datasets.

Developed by [ESnet](https://es.net) engineers, the Science DMZ model addresses common network performance problems encountered at research institutions by creating an environment that is tailored to the needs of high performance science applications, including high-volume bulk data transfer, remote experiment control, and data visualization. 

The Science DMZ architecture also maintains the security of the data through a number of distinct techniques, but does not employ commercial firewalls due to their negative impact on performance. As a result, the Science DMZ model is not currently employed in environments subject to the [HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/) and [HITECH](https://www.hhs.gov/hipaa/for-professionals/special-topics/hitech-act-enforcement-interim-final-rule/) requirements, due to the presumed technical controls based on de facto use of stateful and deep packet–inspecting commercial firewalls. 

We have taken a central of tenet of the Science DMZ, and reengineered it for "restricted data" as a [*Medical Science DMZ*](https://academic.oup.com/jamia/article/doi/10.1093/jamia/ocx104/4367749/The-medical-science-DMZ-a-network-design-pattern).  We have defined a Medical Science DMZ as a method or approach that allows data flows at scale while simultaneously addressing the HIPAA Security Rule and related regulations governing biomedical data and appropriately managing risk.  We emphasize use cases that involve scientists transferring and processing medical research data that have very different requirements than those of medical centers communicating with suppliers, service providers, and employees.  Our network design pattern addresses Big Data and can be implemented using a combination of physical, administrative, and technical safeguards.

### Cite the Medical Science DMZ

Two versions of our Medical Science DMZ paper have been published in [Journal of the American Medical Informatics Association (JAMIA)](http://jamia.oxfordjournals.org) --- a "[brief communication][BC]" in JAMIA 23(6), November 2016, and a "full" version in JAMIA 25(3), March 2018.  Citation information for the "[full][Full]" version of our Medical Science DMZ paper -- the canonical citation -- is as follows:

[BC]: http://jamia.oxfordjournals.org/content/23/6/1199.article-info
[Full]: https://academic.oup.com/jamia/article/doi/10.1093/jamia/ocx104/4367749/The-medical-science-DMZ-a-network-design-pattern

> Sean Peisert, Eli Dart, William K. Barnett, James Cuff, Robert L. Grossman, Edward Balas, Ari Berman, Anurag Shankar, and Brian Tierney, "[The Medical Science DMZ: A Network Design Pattern for Data-Intensive Medical Science](https://academic.oup.com/jamia/article/doi/10.1093/jamia/ocx104/4367749/The-medical-science-DMZ-a-network-design-pattern)," *Journal of the American Medical Informatics Association (JAMIA)*, 26(3):267–274, March 1, 2018.  DOI:[10.1093/jamia/ocx104](http://dx.doi.org/10.1093/jamia/ocx104)

```
@article{MedicalScienceDMZ-2018-JAMIA-Full,
	Author = {Sean Peisert and Eli Dart and Barnett, William K. and James Cuff and Grossman, Robert L. and Edward Balas and Ari Berman and Anurag Shankar and Brian Tierney},
	Journal = {Journal of the American Medical Informatics Association (JAMIA)},
	Month = {March 1},
	Number = {3},
	Pages = {267--274},
	Title = {{The Medical Science DMZ: A Network Design Pattern for Data-Intensive Medical Science}},
	Volume = {26},
	Year = {2018}}
```
