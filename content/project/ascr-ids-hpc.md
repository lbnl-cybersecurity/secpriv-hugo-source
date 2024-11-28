+++
title = "A Mathematical and Data-Driven Approach to Intrusion Detection for High-Performance Computing"
date = 2010-10-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning"]`
tags = ["HPC","machine learning","network","research cyberinfrastructure","secure systems"]

# Project summary to display on homepage.
summary = "This project developed mathematical and statistical techniques to analyze the secure access and use of high-performance computer systems. It was funded by DOE ASCR and was originally led by David H. Bailey."

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


In this project, CRD researchers developed mathematical and statistical techniques to analyze the secure access and use of high-performance computer systems.  The project was funded by the U.S. Department of Energy's Applied Mathematics Section. 

The overall goals of the project were to develop mathematical and statistical methods to detect intrusions of high-performance computing systems.  Our mathematical analysis is predicated on the fact that large HPC systems represent unique environments, quite unlike unspecialized systems or general Internet traffic.  User behavior on HPC systems tends to be much more constrained (often driven by research deadlines and limited computational resources), and is generally limited to certain paradigms of computation (the set of codes performing the bulk of execution provide a rich source of information). In addition, the collaboration networks of users on an HPC system exhibits special characteristics than can be exploited to detect misuse or fraud.   In this research work, we employed real system data, which we have obtained in collaboration with staff in the NERSC Division of LBNL.

LBNL was this lead institution for this activity, which also involved the University of California at Davis (UC Davis) and the International Computer Science Institute (ICSI) at UC Berkeley through LBNL subcontracts.  Over the course of the project, LBNL senior investigators included Deb Agarwal, David H. Bailey (PI), Scott Campbell, Juan Meza, Sean Peisert, Taghrid Samak, and Alexander Slepoy.  The UC Davis senior investigators were Sean Peisert (joint appointment) and Matt Bishop. ICSI senior investigators included Vern Paxson and Robin Sommer.  The research team was supported in their software development and data collection techniques by the staff at the National Energy Research Scientific Computing Center (NERSC).  A variety of students and postdocs at the Berkeley Lab, UC Berkeley, and UC Davis, were also involved, as were external collaborators (not funded by this grant), at Mt. Sinai School of Medicine and the University of San Francisco.

Key work included:

*   The adaptation and development of a "rule-ensemble" technique from the field of mathematical statistics to accurately and economically finds class labels, and to determine which parameter constraints are most useful for predicting these labels.
*   The development and application of a technique of fingerprinting computation on HPC machines based on network theory and machine learning.
*   An examination of Domain Name Server (DNS) traffic using entropy analysis.
*   Development of data sanitization techniques, so that real cybersecurity data can be shared with a wider community of researchers without compromising user privacy.
*   Development of a script to generate a set of synthetic jobs, which then can be used to test job fingerprint algorithms.

A selected list of publications resulting from this project follows.

#### 2013

Orianna DeMasi, Taghrid Samak, David H. Bailey, ["Identifying HPC Codes via performance logs and machine learning",](http://www.davidhbailey.com/dhbpapers/ICS2013-identifying.pdf) Proceedings of the First Workshop on Changing Landscapes in HPC Security, June 17, 2013,

Sean Whalen, Sean Peisert, Matt Bishop, ["Multiclass Classification of Distributed Memory Parallel Computations",](http://www.escholarship.org/uc/item/6mq830qz) Pattern Recognition Letters (PRL), February 2013, 34(3):322-329, [doi: 10.1016/j.patrec.2012.10.007](http://dx.doi.org/10.1016/j.patrec.2012.10.007)

Taghrid Samak, Christine Morin, David H. Bailey, ["Energy consumption models and predictions for large-scale systems",](http://www.davidhbailey.com/dhbpapers/grid5K-hppac-2013.pdf) Proceedings of the Ninth Workshop on High-Performance, Power-Aware Computing, January 22, 2013, to appea,

#### 2012

Sophie Engle, Sean Whalen, ["Visualizing Distributed Memory Computations with Hive Plots",](http://dl.acm.org/citation.cfm?doid=2379690.2379698) Proceedings of the 9th ACM International Symposium on Visualization for Cyber Security (VizSec), Seattle, WA, ACM, October 15, 2012, 56-63, [doi: 10.1145/2379690.2379698](http://dx.doi.org/10.1145/2379690.2379698)

David H. Bailey, Orianna DeMasi, Juan Meza, ["Feature selection and multi-class classification using a rule ensemble method",](http://www.davidhbailey.com/dhbpapers/Ensemble-CIKM.pdf) May 25, 2012,

Sean Whalen, Sophie Engle, Sean Peisert, Matt Bishop, "[Network-Theoretic Classification of Parallel Computation Patterns](http://www.escholarship.org/uc/item/0g3653gc)," _International Journal of High Performance Computing Applications (IJHPCA)_, 26(2):159-169, May 2012. [doi: 10.1177/1094342012436618](http://dx.doi.org/10.1177/1094342012436618)

#### 2011

Matt Bishop, Justin Cummins, Sean Peisert, Bhume Bhumitarana, Anhad Singh, Deborah Agarwal, Deborah Frincke, Michael Hogarth, ["Relationships and Data Sanitization: A Study in Scarlet",](http://www.escholarship.org/uc/item/56n796pq) Proceedings of the 2010 New Security Paradigms Workshop (NSPW), Concord, MA, ACM, September 2011, 151-164, [doi: 10.1145/1900546.1900567](http://dx.doi.org/10.1145/1900546.1900567)

Orianna DeMasi, Juan Meza and David H. Bailey, ["Dimension reduction using rule ensemble machine learning methods: A numerical study of three ensemble methods",](http://www.davidhbailey.com/dhbpapers/Ensemble_TechReport.pdf) August 30, 2011,

Sean Whalen, Sean Peisert, Matt Bishop, ["Network-Theoretic Classification of Parallel Computation Patterns",](http://www.cs.ucdavis.edu/~peisert/research/2011-CACHES-ntc.pdf) Proceedings of the First International Workshop on Characterizing Applications for Heterogeneous Exascale Systems (CACHES), Tucson, AZ, IEEE Computer Society, June 4, 2011,

#### 2010

Sean Whalen, Matt Bishop, James Crutchfield, ["Hidden Markov Models for Automated Protocol Learning",](Sean Whalen, Matt Bishop and James Crutchfield) Proceedings of the 6th International ICST Conference on Security and Privacy in Communications Networks (SecureComm), Singapore, September 2010, [doi: 10.1007/978-3-642-16161-2_24](http://dx.doi.org/10.1007/978-3-642-16161-2_24)

Sean H. Whalen, _[Security Applications of the ε-Machine](http://proquest.umi.com/pqdweb?did=2196666581&sid=5&Fmt=2&clientId=1567&RQT=309&VName=PQD)_, Ph.D. Dissertation, Dept. of Computer Science, University of California, Davis,, September 2010,

Sean Peisert, ["Fingerprinting Communication and Computation on HPC Machines",](http://escholarship.org/uc/item/7121p0xd) Lawrence Berkeley National Laboratory Technical Report, June 2010, LBNL LBNL-3483E,

Robin Sommer, Vern Paxson, ["Outside the Closed World: On Using Machine Learning For Network Intrusion Detection",](http://dx.doi.org/10.1109/SP.2010.25) Proceedings of the 31st IEEE Symposium on Security and Privacy, Oakland, CA, IEEE Computer Society, May 2010, 305–316, [doi: 10.1109/SP.2010.25](http://dx.doi.org/10.1109/SP.2010.25)


### Funding

This project was supported by the US Department of Energy's Office of Science's [Advanced Scientific Computing Research (ASCR)](http://science.energy.gov/ascr/) program.

More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for research cyberinfrastructure and high-performance computing](/research/research-cyberinfrastructure/).
