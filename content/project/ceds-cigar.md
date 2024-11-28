+++
title = "Cybersecurity via Inverter-Grid Automatic Reconfiguration (CIGAR)"
date = 2021-03-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning"]`
tags = ["power grid","machine learning","AI"]

# Project summary to display on homepage.
summary = "This project performed research to enable distribution grids to adapt to resist a cyber-attack by (1) developing adaptive control algorithms for DER, voltage regulation, and protection systems; (2) analyze new attack scenarios and develop associated defensive strategies. It was funded by DOE's CEDS program and was co-led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) and [Daniel Arnold](https://eta.lbl.gov/people/daniel-arnold)."

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


## Background

The proliferation of Distributed Energy Resources (DER) in electric distribution systems is challenging many existing conventional paradigms of how the grid is planned and operated. This includes strategies to ensure the safety of the electric grid from cyber attacks.  Aggregations of DER constitute a mechanism through which hostile entities can remotely influence multiple systems and states in the grid in such a way that distribution system operators have virtually no warning of an attack and no clear strategy to mitigate the effects of intrusion. Furthermore, as infrastructure already exists to reconfigure DER smart inverter settings, attackers need not infiltrate individual systems to gain control over large quantities of DER. Instead, attackers need only gain access to one of a handful of systems designed to wirelessly update DER.

## Objectives

- Development of a state observer that detects the presence and severity of cyber attacks.
- Creation of a set of adaptive controllers that adjust settings of DER inverter controllers and distribution grid voltage regulation and protection systems to mitigate the cyber-physical attack in real time.
- Development of reinforcement learning-based agents that will explore defenses against different attack scenarios

## Project Description

The LBNL-led "Cybersecurity via Inverter-Grid Automatic Reconfiguration (CIGAR)" project seeks to develop supervisory control algorithms to counteract cyber-physical attacks that have compromised multiple independent systems in the electric grid. This research will begin with an effort to analyze the stability of different types of feedback control systems (e.g, distributed energy resources, and voltage regulation and protection systems) in the electric grid to determine what parameters an attacker would change if DER and utility voltage regulation and protection systems were compromised. Then, the research team will develop adaptive control algorithms that adjust critical parameters in non-compromised systems to actively fight the cyber-physical attack. Finally, this project will utilize reinforcement learning techniques to simultaneously develop defense strategies in higher dimensions tailored to specific sections of the electric grid.  Analysis of derived attack and defensive strategies will also highlight specific system vulnerabilities as well as determine recommended upgrades to enhance system cyber security.

This project was supported by the U.S. Department of Energy's [Cybersecurity for Energy Delivery Systems (CEDS)](https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and) program.

DOE/LBNL Press Release: "[Berkeley Lab Aims to Strengthen the Cybersecurity of the Grid](http://newscenter.lbl.gov/2017/09/26/berkeley-lab-aims-to-strengthen-the-cybersecurity-of-the-grid/)," September 26, 2017.

#### Principal Investigators:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI; LBNL)  
[Daniel Arnold](https://eta.lbl.gov/people/daniel-arnold) (Co-PI; LBNL)

#### Senior Personnel:
[Reinhard Gentz](https://crd.lbl.gov/divisions/scidata/idf/staff/reinhard-gentz/) (LBNL)  \
[Ciaran Roberts](http://eetd.lbl.gov/people/ciaran-roberts) (LBNL) \
[Sy-Toan Ngo](https://eta.lbl.gov/people/sy-toan-ngo) (LBNL)\
[David Pinney](https://www.linkedin.com/in/davidwpinney/) (Lead at NRECA) \
[Anna Scaglione](https://scaglione.engineering.asu.edu) (Lead at ASU)  \
[Dmitriy Fradkin](https://www.linkedin.com/in/dmitriy-fradkin-6526272/) (Lead at Siemens)  \
[Sindhu Suresh](https://www.linkedin.com/in/sindhu-suresh-ph-d-pmp-csm-80656b18/) (Siemens) \
[Anton Kocheturov](https://www.linkedin.com/in/anton-kocheturov-611914a2/) (Siemens)

#### Students:
[Ewa Garbiec](https://www.linkedin.com/in/ewa-garbiec-5809a0156/) (UC Dublin) \
[Ignacio Losada Carreño][Ignacio] (ASU) \
[Alexandre Milesi](https://milesial.github.io) (Univ. Tech. Compiègne) \
[Shammya Saha][38] (ASU)  

[Ignacio]: https://www.linkedin.com/in/ignacio-losada-0879457b/
[38]: https://www.linkedin.com/in/shammya-saha/

#### Partners:
[Arizona State University](https://www.asu.edu)  
[National Rural Electric Cooperative Association (NRECA)](http://www.nreca.coop)    
[Siemens](https://www.siemens.com)  

### Project Workshops:
[End of Project Workshop](/talk/ceds_cigar_y3_workshop/)

### Press regarding this project:

[Solar power opens up new targets for cyber attackers](https://archerint.com/solar-power-opens-up-new-targets-for-cyber-attackers/) (Archer News) — May 30, 2019

[Cyberattacks threaten smart inverters, but scientists have solutions](https://www.solarpowerworldonline.com/2019/04/cyberattacks-threaten-smart-inverters-but-scientists-have-solutions/) (Solar Power World) — April 30, 2019

[Cyber Defense Tool Is an Early Warning System for Grid Attacks](https://spectrum.ieee.org/energywise/energy/the-smarter-grid/cyber-defense-tool-targets-grid-vulnerability) (IEEE Spectrum Energywise Blog) — March 27, 2018

[Berkeley Lab Aims to Strengthen the Cybersecurity of the Grid](http://newscenter.lbl.gov/2017/09/26/berkeley-lab-aims-to-strengthen-the-cybersecurity-of-the-grid/) — September 27, 2017

### Presentations relating to this project:

Sean Peisert, “Cybersecurity and Privacy research for Science and Energy,” [Networking and Information Technology Research and Development (NITRD) Cyber Security and Information Assurance (CSIA) Interagency Working Group (IWG)](https://www.nitrd.gov/coordination-areas/csia/) Meeting, March 24, 2022.

### Publications resulting from this project:

Sean Peisert, Daniel Arnold, Ciaran Roberts, Sy-Toan Ngo, Michael Sankur, Anna Scaglione, Ignacio Losada Carreno, Shammya Saha Anton Kocheturov, Dmitriy Fradkin, David Pinney, Ryan Mahoney, Lisa Slaughter, "[Cybersecurity via Inverter Grid Automatic Reconfiguration (CIGAR) Year 3 Report](https://escholarship.org/uc/item/8c13q45x)," March 31 2021.

Ciaran Roberts, Sy-Toan Ngo, Alexandre Milesi, Anna Scaglione, Sean Peisert, Daniel Arnold, "[Deep Reinforcement Learning for Mitigating Cyber-Physical DER Voltage Unbalance Attacks](https://doi.org/10.23919/ACC50511.2021.9482815)," Proceedings of the [2021 American Control Conference (ACC)](https://acc2021.a2c2.org), May 26–28, 2021. \[[arXiv](https://arxiv.org/pdf/2009.13088)\]


Shammya Shananda Saha, Daniel Arnold, Anna Scaglione, Eran Schweitzer, Ciaran Roberts, Sean Peisert, and Nathan G. Johnson. "[Lyapunov Stability of Smart Inverters Using Linearized DistFlow Approximation](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/rpg2.12009)," _[IET Renewable Power Generation](https://digital-library.theiet.org/content/journals/iet-rpg)_, accepted 28 September 2020. \[[arXiv](https://arxiv.org/abs/2011.09620)\]

Ignacio Losada Carreño, Raksha Ramakrishna, Anna Scaglione, Daniel Arnold, Ciaran Roberts, Sy-Toan Ngo, Sean Peisert, and David Pinney, "[SoDa: An Irradiance-Based Synthetic Solar Data Generation Tool](https://escholarship.org/uc/item/6cp617fw),”   _Proceedings of the [IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)](https://sgc2020.ieee-smartgridcomm.org)_, November 11–13, 2020.

Ciaran Roberts Sy-Toan Ngo, Alexandre Milesi, Sean Peisert, Daniel Arnold, Shammya Saha, Anna Scaglione, Nathan Johnson, Anton Kocheturov, Dmitriy Fradkin, "[Deep Reinforcement Learning for DER Cyber-Attack Mitigation](https://escholarship.org/uc/item/5069z5wn)," _Proceedings of the [IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)](https://sgc2020.ieee-smartgridcomm.org)_, November 11–13, 2020.

More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for energy delivery systems](/research/ceds/).
