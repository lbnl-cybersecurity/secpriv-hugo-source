+++
title = "Cyber Security of Power Distribution Systems by Detecting Differences Between Real-time Micro-Synchrophasor Measurements and Cyber-Reported SCADA"
date = 2014-09-15
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["power grid","machine learning","cyber-physical systems","network"]

# Project summary to display on homepage.
summary = "This project used micro-PMU measurements and SCADA commands to develop a system to detect cyberattacks against the power distribution grid. It was funded by DOE OE's CEDS program and was led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/)."

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


The power distribution grid, like many cyber physical systems, was developed with careful consideration for safe operation. However, a number of features of the power system make it particularly vulnerable to cyber attacks via IP networks. "IT security" approaches to dealing with malware and other cyber attacks via a network include traditional intrusion detection systems, firewalls, encryption, etc... These techniques can help, but as we've observed in a [previous project](/project/ceds-cps-security/), traditional IT security techniques tend to leave a gap in safety and protection when applied to cyber-physical devices because they do not consider physical information known about the cyber-physical device they are protecting. Not only does this leave a gap in protection, but it ignores valuable information that could be used to better protect the cyber-physical device.  
  
The goal of this is to design and implement a measurement network, which can detect and report the resultant impact of cyber security attacks on the distribution system network. The cyber-attacks against the distribution grid that we primarily focus on are ones that (1) modify the distribution grid operation and causing it to behave in individually or collectively disruptive or damaging ways; (2) mask communication from substation components in the distribution grid, through cyber denial-of-service attack, and prevent awareness of the actual operational function; and (3) mask communication to substation components in the distribution grid, through cyber denial of service attack, causing misbehaving components to fail to receive instructions to restore safe operation. The detection and reporting will be within short time frame, at present not communicable or measured on the distribution system, allowing operators to perform remedial action.  
  
To do this, this project uses micro phasor measurement units to capture information about the physical state of the power distribution grid and combines this with SCADA command monitoring in real time. The project will build models of safe and unsafe states of the distribution grid so that certain classes cyber attacks can potentially be detected by their physical effects on the power distribution grid alone. The result will be a system that provides an independent, integrated picture of the distribution grid's physical state, which will be difficult for a cyber-attacker to subvert using data-spoofing techniques.

See the detection algorithms in action via our graphical front-end at the [LBNL Power Data Portal](http://powerdata.lbl.gov).

Source code for the [LBNL Stream-Processing Architecture for Real-time Cyber-physical Security (SPARCS) is available at GitHub](https://github.com/lbnl-cybersecurity/sparcs).



This project is supported by the U.S. Department of Energy's [Cybersecurity for Energy Delivery Systems (CEDS)](http://energy.gov/oe/services/technology-development/energy-delivery-systems-cybersecurity) program.

#### Principal Investigators:

[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI; LBNL)  
[Ciaran Roberts](http://eetd.lbl.gov/people/ciaran-roberts-0) (Co-PI; LBNL)  
[Anna Scaglione](http://lab.engineering.asu.edu/scaglione/) (Co-PI; ASU)

#### Senior Personnel

[Reinhard Gentz](https://crd.lbl.gov/divisions/scidata/idf/staff/reinhard-gentz/) (LBNL)

#### Students

[Mahdi Jamei](https://www.linkedin.com/profile/view?id=193336997) (ASU)

#### Industry Partners:

[EnerNex](http://www.enernex.com/) ([Erich Gunther](http://www.enernex.com/employees/erich-gunther/) (previously), [Aaron Snyder](http://www.enernex.com/employees/aaron-snyder/), [Bob Zavadil](http://www.enernex.com/employees/robert-zavadil/), [Dave Mueller,](http://www.enernex.com/employees/david-mueller/) [Jens Schoene](http://www.enernex.com/employees/jens-schoene/))  
[EPRI](http://www.epri.com/) ([Galen Rasche](https://www.linkedin.com/in/galen-rasche-06238011), [Jens Boemer)](https://www.linkedin.com/in/jcboemer)  
[Power Standards Laboratory](http://www.powerstandards.com/) ([Alex McEachern](http://powerstandards.com/McEachern/index.htm))  
[Corelight](http://corelight.io) (née [Broala](https://www.broala.com))  
[OSIsoft](http://www.osisoft.com/) ([John Matranga](https://www.linkedin.com/in/johnmatranga))  
[Riverside Public Utilities](http://www.riversideca.gov/utilities/)  
[Southern Company](http://southerncompany.com)

#### Project Alumni:

[Chuck McParland](https://crd.lbl.gov/divisions/scidata/idf/affiliates/charles-mcparland/) (Former Co-PI; LBNL → RTISYS / LBNL Affiliate)[  
](http://www.enernex.com/)[Emma Stewart](http://eetd.lbl.gov/people/emma-stewart) (Former Co-PI; LBNL → LLNL)

### Press regarding this project:

[Electric grid protection through low-cost sensors, machine learning](https://gcn.com/articles/2018/09/21/grid-cybersecurity.aspx?m=1) (GCN) — September 21, 2018

[Cyber Defense Tool Is an Early Warning System for Grid Attacks](https://spectrum.ieee.org/energywise/energy/the-smarter-grid/cyber-defense-tool-targets-grid-vulnerability) (IEEE Spectrum Energywise Blog) — March 27, 2018

[Combination of Old and New Yields Novel Power Grid Cybersecurity Tool](https://cs.lbl.gov/news-media/news/2018/combination-of-old-and-new-yields-novel-power grid-cybersecurity-tool/) — March 7 2018

### Publications resulting from this project:

Mahdi Jamei, Raksha Ramakrishna, Teklemariam Tesfay, Reinhard Gentz, Ciaran Roberts, Anna Scaglione, and Sean Peisert, "[Phasor Measurement Units Optimal Placement and Performance Limits for Fault Localization](https://www.cs.ucdavis.edu/~peisert/research/2020-JSAC-PMULocalization)," _[IEEE Journal on Selected Areas in Communications (J-SAC)](https://www.comsoc.org/publications/journals/ieee-jsac)_, _[Special Issue on Communications and Data Analytics in Smart Grid](https://www.comsoc.org/publications/journals/ieee-jsac/cfp/communications-and-data-analytics-smart-grid)_, accepted 2 October, 2019.  \[[DOI](https://doi.org/10.1109/JSAC.2019.2951971)\]

Ciaran Roberts, Anna Scaglione, Mahdi Jamei, Reinhard Gentz, Sean Peisert, Emma M. Stewart, Chuck McParland, Alex McEachern, and Daniel Arnold, "[Learning Behavior of Distribution System Discrete Control Devices for Cyber-Physical Security](https://escholarship.org/uc/item/8hf0c89n)," _[IEEE Transactions on Smart Grid](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5165411)_, accepted 31 July, 2019.  \[[DOI](http://doi.org/10.1109/TSG.2019.2936016)\]

Reinhard Gentz, Sean Peisert, Joshua Boverhof, Daniel Gunter, "SPARCS: Stream-Processing Architecture applied in Real-time Cyber-physical Security" _Proceedings of the [15th IEEE International Conference on e-Science (eScience)](http://escience2019.sdsc.edu/)_, San Diego, CA, September 2019.

Mahdi Jamei, [_Security Analysis of Interdependent Critical Infrastructures: Power, Cyber and Gas_](https://repository.asu.edu/attachments/211287/content/Jamei_asu_0010E_18341.pdf), PhD dissertation, Arizona State University, December 2018.

Mahdi Jamei, Anna Scaglione, and Sean Peisert, "[Low-Resolution Fault Localization Using Phasor Measurement Units with Community Detection](https://arxiv.org/pdf/1809.04014v1.pdf)," _Proceedings of the [2018 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)](http://sgc2018.ieee-smartgridcomm.org/)_, Allborg, Denmark, October 29--31, 2018.

Sean Peisert, Ciaran Roberts, Anna Scaglione, Mahdi Jamei, Reinhard Gentz, Charles McParland, Alex McEachren, Galen Rasche, Aaron Snyder, "[Supporting Cyber Security of Power Distribution Systems by Detecting Differences Between Real-time Micro-Synchrophasor Measurements and Cyber-Reported SCADA - Final Report](https://escholarship.org/uc/item/4fr3h63c)," October 15, 2018.

Ciaran Roberts, Anna Scaglione and Sean Peisert, "[A Holistic Approach to Distribution Grid Intrusion Detection Systems](https://www.energycentral.com/c/gr/holistic-approach-distribution-grid-intrusion-detection-systems)," [EnergyCentral](https://www.energycentral.com/), July 18, 2018

Mahdi Jamei, Anna Scaglione, Ciaran Roberts, Emma Stewart, Sean Peisert, Chuck McParland, and Alex McEachern, “[Anomaly Detection Using μPMU Measurements in Distribution Grids](https://escholarship.org/uc/item/3zf1f06g),” _[IEEE Transactions on Power Systems](https://www.ieee-pes.org/ieee-transactions-on-power-systems),_ 33(4):3611--3623, July 2018.

Mahdi Jamei, Anna Scaglione, Ciaran Roberts, Alex McEachern, Emma Stewart, Sean Peisert, and Chuck McParland, “[Online Thevenin Parameter Tracking Using Synchrophasor Data](http://www.escholarship.org/uc/item/7zx481ff),” _Proceedings of the [2017 IEEE Power Engineering Society (PES) General Meeting (GM)](http://www.pes-gm.org/2017/)_, Chicago, IL, July 16--20, 2017

Reinhard Gentz, [_Wireless Sensor Data Transport, Aggregation and Security,_](https://search.proquest.com/docview/1949775503) Ph.D. Dissertation, Arizona State University, July 2017.

Mahdi Jamei, Anna Scaglione, Ciaran Roberts, Emma Stewart, Sean Peisert, Chuck McParland, and Alex McEachern, “[Automated Anomaly Detection in Distribution Grids Using µPMU Measurements](http://www.escholarship.org/uc/item/8pj28949),” _Proceedings of the 50th [Hawaii International Conference on System Sciences (HICSS)](http://www.hicss.org)_, Electric Energy Systems Track, Resilient Networks Minitrack, Waikoloa, HI, Jan. 4–7, 2017.

Mahdi Jamei, Emma Stewart, Sean Peisert, Anna Scaglione, Chuck McParland, Ciaran Roberts, and Alex McEachern, "[Micro Synchrophasor-Based Intrusion Detection in Automated Distribution Systems: Towards Critical Infrastructure Security](http://www.escholarship.org/uc/item/84j8f0md)," _[IEEE Internet Computing](http://computer.org/internet/)_," Sept./Oct. 2016. \[[CDL](http://www.escholarship.org/uc/item/84j8f0md)\]


### Software resulting from this project:

[LBNL Stream-Processing Architecture for Real-time Cyber-physical Security (SPARCS)](https://github.com/lbnl-cybersecurity/sparcs)

**Analytics for Stream-Processing Architecture for Real-time Cyber-physical Security (Analytic-SPARCS).**  

More information is available on other Berkeley Lab R&D projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for energy delivery systems](/research/ceds/).
