+++
title = "Provable Anonymization of Grid Data for Cyberattack Detection"
date = 2022-08-27
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["differential privacy","power grid","machine learning","cyber-physical systems","data privacy"]

# Project summary to display on homepage.
summary = "This project aims to develop techniques for enabling data analysis for the purposes of detecting and/or investigating cyberattacks against energy delivery systems while also preserving aspects of key confidentiality elements within the underlying raw data being analyzed. The result will be a complete solution for anonymization of data collected from OT and IT networks pertaining to energy grid cyberattack detection that has been tested for its ability to retain privacy properties and still enable attack detection.  It is funded by DOE CESER's CEDS program and is led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/)."

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

Data is frequently not shared by organizations because that data is considered by the organization to be in some way sensitive. For example, there may be laws or regulations prohibiting sharing due to personal privacy or national security issues, or the organization owning the data may also consider that data to be a proprietary trade secret. In any case, that data cannot or will not be released in raw form, and so alternative approaches are needed if that data is to be shared at all.

Today, data is often not shared at all, or if it is shared, it is done so in ways that require people processing or analyzing that data to access the data in highly secured, non-networked environments set up to prevent any data from being exfiltrated either physically from a building or certainly from a network. This is the reason why much research is hindered.  Sometimes data is shared through processes of "anonymization" in which data is typically either masked or made more general.  Unfortunately, these techniques have repeatedly been shown to fail, typically by merging external information containing identifiable information with quasi-identifiers contained in the dataset in order to identify "anonymized" records in the dataset. 

This project aims to develop techniques for enabling data analysis for the purposes of detecting and/or investigating cyberattacks against energy delivery systems while also preserving aspects of key confidentiality elements within the underlying raw data being analyzed.  Specifically, this project proposes to examine the application of privacy-preserving techniques to OT and grid-security-relevant IT data provided by the California Energy Commission (CEC), Kevala, and Portland General Electric, in order to protect privacy as much as possible, thereby minimizing the amount of data for which "traditional" (and vulnerable) anonymization techniques need to be applied.  The result will be a solution for anonymization of data collected from OT and IT networks pertaining to energy grid cyberattack detection that has been tested for its ability to retain privacy properties and still enable attack detection.

This project is supported by the U.S. Department of Energy's [Cybersecurity for Energy Delivery Systems (CEDS)](https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and) program.

DOE Press Release: "[Department of Energy Announces Awardees of $30 Million Research Call to Enhance Cybersecurity for Energy Delivery Systems](https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and)," August 27, 2019.

#### Principal Investigator:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI; LBNL)  

#### Co-Leads:
[Anna Scaglione](https://sinelab.tech.cornell.edu/anna-scaglione/) (Lead at Cornell Tech)  \
[Aram Shumavon](https://www.linkedin.com/in/aram-shumavon-3a8472/) (Lead at Kevala)  

#### Postdocs:
[Tong Wu](https://sinelab.tech.cornell.edu/research/people/tong_wu/) ([Cornell Tech](https://www.tech.cornell.edu))

#### Graduate Students:
[Andrew Campbell](https://sinelab.tech.cornell.edu/research/people/andrew_campbell/) \
[Nikhil Ravi](https://nikhil-ravi.github.io) (Cornell Tech) \
[Leah Woldemariam](https://sinelab.tech.cornell.edu/research/people/leah_woldemariam/)

#### Partners:
[Cornell Tech](https://www.tech.cornell.edu)  
[Kevala, Inc.](https://kevalaanalytics.com)  
[California Energy Commission](https://energy.ca.gov)    
[Portland General Electric](https://www.portlandgeneral.com)  
[SunPower](hhttps://www.SunPower.com)  

#### Past Researchers:
[Rojin Zandi](https://sinelab.tech.cornell.edu/research/people/rojin_zandi/) (Cornell Tech) \
[Sachin Kadam](https://www.public.asu.edu/~skadam6/) (ASU) \
[Daniel Arnold](https://eta.lbl.gov/people/daniel-arnold) (LBNL) \
[Reinhard Gentz](https://crd.lbl.gov/divisions/scidata/idf/staff/reinhard-gentz/) (LBNL) \
[Raksha Ramakrishnan](https://www.linkedin.com/in/raksha-ramakrishna-b4390374/) (KTH) \
[Ciaran Roberts](http://eetd.lbl.gov/people/ciaran-roberts-0) (LBNL) 



<!--
#### Past Postdocs:
-->

#### Past Partners:
[Arizona State University](https://www.asu.edu)  

### Press regarding this project:

[Scientific Data Division Summer Students Tackle Data Privacy](https://crd.lbl.gov/news-and-publications/news/2022/scientific-data-division-summer-students-tackle-data-privacy/) - Sept. 15, 2022

### Presentations relating to this project:

Sean Peisert, “Cybersecurity and Privacy research for Science and Energy,” [Networking and Information Technology Research and Development (NITRD) Cyber Security and Information Assurance (CSIA) Interagency Working Group (IWG)](https://www.nitrd.gov/coordination-areas/csia/) Meeting, March 24, 2022.


### Publications resulting from this project:

Tong Wu, Anna Scaglione, Adrian Petru Surani, Daniel Arnold, and Sean Peisert, "Network-Constrained Reinforcement Learning for Optimal EV Charging Control,” Proceedings of the _[IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)](https://sgc2023.ieee-smartgridcomm.org)_, October 31–November 3, 2023.

Robert Currie, Sean Peisert, Anna Scaglione, Aram Shumavon, and Nikhil Ravi, "Data Privacy for the Grid: Toward a Data Privacy Standard for Inverter-Based and Distributed Energy Resources," _[IEEE Power & Energy Magazine](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8014)_, 21(5), pp. 58-57, Sept.-Oct 2023.

Sachin Kadam, Anna Scaglione, Nikhil Ravi, Sean Peisert, Brent Lunghino, and Aram Shumavon, “[Optimum Noise Mechanism for Differentially Private Queries in Discrete Finite Sets](https://doi.org/10.1109/MPE.2023.3288595),” _Proceedings of the 2023 [IEEE International Conference on Smart Applications](https://smartnets.ieee.tn/)_, Communications and Networking (SmartNets), Istanbul, Turkey, July 25–27, 2023.

Raksha Ramakrishna, Anna Scaglione, Tong Wu, Nikhil Ravi, and Sean Peisert, “[Differential Privacy for Class-based Data: A Practical Gaussian Mechanism](https://doi.org/10.48550/arXiv.2306.05578),” to appear in _[IEEE Transactions on Information Forensics and Security](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)_, 2023.

Nikhil Ravi, Anna Scaglione, Julieta Giraldez, Parth Pradhan, Chuck Moran, and Sean Peisert, "Solar Photovoltaic Systems Metadata Inference and Differentially Private Publication," *arXiv preprint* [arXiv:2304.03749](https://arxiv.org/abs/2304.03749) 7 Apr 2023.

Nikhil Ravi, Anna Scaglione, Sachin Kadam, Reinhard Gentz, Sean Peisert, Brent Lunghino, Emmanuel Levijarvi, and Aram Shumavon, "[Differentially Private *K*-means Clustering Applied to Meter Data Analysis and Synthesis](https://doi.org/10.1109/TSG.2022.3184252)," _[IEEE Transactions on Smart Grid](https://www.ieee-pes.org/ieee-transactions-on-smart-grid)_, June 17, 2022.

Anna Scaglione, "[The Use of Differential Privacy for Energy Data](https://doi.org/10.1145/3494107.3522780)," _Proceedings of the [8th ACM on Cyber-Physical System Security Workshop (CPSS '22)](https://illinois.adsc.com.sg/CPSS2022/)_, May 30-June 2, 2022.  https://doi.org/10.1145/3494107.3522780

Nikhil Ravi, Anna Scaglione, Sachin Kadam, Reinhard Gentz, Sean Peisert, Brent Lunghino, Emmanuel Levijarvi, Aram Shumavon, "Differentially Private *K*-means Clustering Applied to Meter Data Analysis and Synthesis," *arXiv preprint* [arXiv:2112.03801](https://arxiv.org/abs/2112.03801), 7 Dec 2021.

Sachin Kadam, Anna Scaglione, Nikhil Ravi, Sean Peisert, Brent Lunghino, and Aram Shumavon, "Optimum Noise Mechanism for Differentially Private Queries in Discrete Finite Sets," *arXiv preprint* [arXiv:2111.11661](https://arxiv.org/abs/2111.11661), 23 Nov 2021.

Nikhil Ravi, Anna Scaglione, and Sean Peisert, "Colored Noise Mechanism for Differentially Private Clustering," *arXiv preprint* [arXiv:2111.07850](https://arxiv.org/abs/2111.11661), 15 Nov 2021. 


More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for energy delivery systems](/research/ceds/).
