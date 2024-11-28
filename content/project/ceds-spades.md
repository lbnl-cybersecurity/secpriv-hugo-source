+++
title = "Supervisory Parameter Adjustment for Distribution Energy Storage (SPADES)"
date = 2022-08-23
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning"]`
tags = ["power grid","machine learning","AI"]

# Project summary to display on homepage.
summary = "This project is developing the methodology and tools allowing Electric Storage Systems (ESS) to automatically reconfigure themselves to counteract cyberattacks, both directly against the ESS control systems and indirectly through the electric grid. It is funded by DOE CESER's CEDS program and is led by [Daniel Arnold](https://eta.lbl.gov/people/daniel-arnold)."

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

Energy Storage Systems (ESS), such as electric batteries, are increasingly becomming critical components of the electric power system.  As these devices begin to provide grid services, it is critical to ensure that they are resistant to cyber attacks and cannot be exploited as a mechanism to disrupt the operation of the power grid.  Tools from nonlinear and optimal control theory can be utilized to develop control policies to re-dispatch setpoints in both the ESS and the surrounding electric grid infrastructure to mitigate the effect of cyber attacks.

## Objectives

* Characterize the interaction ESS control systems and Distributed Energy Resource (DER) smart inverter functions on electric grid voltage stability.

* Develop a supervisory control system (reinforcement learning-based) that will identify and autonomously update control parameters of the power electronic control systems within ESS devices.  

* Validate control approaches via Hardware-In-the-Loop (HIL) testing at the LBNL FLEXGRID facility.

* Integrate the defensive reinforcement learning-based agent into the NRECA Open Modeling Framework (OMF) simulation tool.



## Project Description



The Supervisory Parameter Adjustment for Distribution Energy Storage (SPADES) project will develop the methodology and tools allowing Energy Storage Systems (ESS) to automatically reconfigure themselves to counteract cyberattacks against both the ESS control system directly and indirectly through the electric distribution grid. This research will begin with an effort to analyze the stability of both ESS control systems and the interaction of the ESS control system and the electric grid, to determine what parameters an attacker would change if a given device (or multiple devices) were to be compromised.  Then, the research team will develop a supervisory control framework that utilizes adaptive control and reinforcement learning techniques to adjust ESS control system parameters and ESS active and reactive power injections to actively defend against a variety of cyberattacks.  The supervisory control framework will be validated in Hardware-in-the-Loop (HIL) experiments where an independent red team will attempt to alter control parameters of an ESS to prevent the device from providing grid services.  The reinforcement learning defensive algorithms will be integrated into the National Rural Electric Cooperative Association (NRECA) Open Modeling Framework (OMF), thereby allowing defensive strategies to be tailored on a utility specific basis.  The major outcomes of this project will be the tools to isolate the component of the ESS control system that has been compromised during a cyberattack as well as policies for changing the control parameters of ESS to mitigate a wide variety of cyberattacks on both the ESS device itself and the electric distribution grid.



This project is supported by the U.S. Department of Energy's [Cybersecurity for Energy Delivery Systems (CEDS)](https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and) program.



#### Principal Investigator:

[Daniel Arnold](https://eta.lbl.gov/people/daniel-arnold) (PI; LBNL)



#### Senior Personnel:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (LBNL) \
[Ciaran Roberts](https://eta.lbl.gov/people/ciaran-roberts) (LBNL) \
[Sy-Toan Ngo](https://eta.lbl.gov/people/sy-toan-ngo) (LBNL) \
[David Pinney](https://www.linkedin.com/in/davidwpinney/) (NRECA) \
[Anna Scaglione](https://scaglione.engineering.asu.edu/) (Cornell Tech) \
[Bruno Leao](https://www.linkedin.com/in/brunoleao/) (Siemens)



#### Partners:

[Cornell Tech](https://www.tech.cornell.edu/)\
[National Rural Electric Cooperative Association (NRECA)](http://www.nreca.coop)\
[Siemens](https://www.siemens.com)  


### Project Workshops and Reports

[Year 1](/talk/ceds_spades_y1_workshop/), held on 12/02/2021  \
[Year 2](/talk/ceds_spades_y2_workshop), held on 12/08/2022 and 12/15/2022 \
[Years 3 and 4](/talk/ceds_spades_y3_report)


### Press regarding this project:

TBD


### Publications resulting from this project:

Wu, T., Scaglione, A., and Arnold, D. “Complex-Value Spatio-temporal Graph Convolutional Neural Networks and its Applications to Electric Power Systems AI,” IEEE Transactions on Smart Grid, early access, https://doi.org/10.1109/TSG.2023.3332591  

Wu, T., Scaglione, A., and Arnold, D., “Constrained Reinforcement Learning for Predictive Control in Real-Time Stochastic Dynamic Optimal Power Flow,” in IEEE Transactions on Power Systems, https://doi.org/10.1109/TPWRS.2023.3326121 

Leao, B. P., Vempati, J., Bhela, S., Ahlgrim, T., and Arnold, D., “Augmented Digital Twin for Identification of Most Critical Cyberattacks in Industrial Systems”, https://doi.org/10.48550/arXiv.2306.04821 

Roberts, C., Arnold, D., and Callaway, D., “An Online Adaptive Damping Controller for Converter-Interfaced Generation.”, IEEE Transactions on Power Systems, vol. 39, no. 2, pp. 3962-3971, March 2024, http://doi.org/10.1109/TPWRS.2023.3286186 

Wu, T., Scaglione, A., and Arnold, D. “Spatio-Temporal Graph Convolutional Neural Networks for Physics-Aware Grid Learning Algorithms,” IEEE Transactions on Smart Grid,  vol. 14, no. 5, pp. 4086-4099, Sept. 2023 https://doi.org/10.1109/TSG.2023.3239740 

Losada Carreno, I., Saha, S. S., Scaglione, A., Arnold, D., Ngo, S., and Roberts, C., “Log(v) 3LPF: A Linear Power Flow Formulation for Unbalanced Three-Phase Distribution Systems,” IEEE Transactions on Power Systems,  vol. 38, no. 1, pp. 100-113, Jan. 2023, doi: https://doi.org/10.1109/TPWRS.2022.3166725 

Arnold, D., Saha, S. S., Ngo, S., Roberts, C., Scaglione, A., Johnson, N., Peisert, S., and Pinney, D., “Adaptive Control of Distributed Energy Resources for Distribution Grid Voltage Stability,” IEEE Transactions on Power Systems, Vol. 38(1), Mar. 2022, pp. 129 - 141. https://doi.org/10.1109/TPWRS.2022.3157558 

Arnold, D., Ngo, S., Roberts, C., Chen, Y., Scaglione, A., and Peisert, S., “Adam-based Augmented Random Search for Control Policies for Distributed Energy Resource Cyber Attack Mitigation,” [American Control Conference](https://acc2022.a2c2.org/), 2022, accepted, available: http://arxiv.org/abs/2201.11825

Roberts, C., Markovic, U., Arnold, D., and Callaway, D. S., “Malicious Control of an Active Load in an Islanded Mixed-Source Microgrid,” Proceedings of 2021 IEEE Madrid PowerTech, Madrid, Spain, July 2021, pp. 1-6. https://doi.org/10.1109/PowerTech46648.2021.9495077 



More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for energy delivery systems](/research/ceds/).
