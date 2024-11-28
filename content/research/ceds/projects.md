+++
# Projects widget.
widget = "portfolio"
headless = true
active = true
weight = 50  # Order that this section will appear in.

title = "Cybersecurity for Energy Delivery Systems Projects"
subtitle = ""

[content]
  page_type = "project"

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "project"

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
  filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
# [[filter]]
#   name = "All"
#   tag = "*"
#  
#  [content.filters]
#   name = "Power"
#   tag = "power grid"
  [[content.filter_button]]
   name = "Power"
   tag = "power-grid"


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Berkeley Lab [Computing Sciences Research][CRD] is an active participant in a number of projects in the arena of cybersecurity for energy delivery systems.  Recently, this work has been funded largely via DOE's [Cybersecurity for Energy Delivery Systems (CEDS) research program](https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and). These projects include collaborations with academic, vendor, and utility partners. 

[CRD]: https://crd.lbl.gov

Berkeley Lab's work in security for power grid control systems emphasizes both its historical role in developing, deploying and testing the [Zeek (Bro) Network Security Monitor](https://www.zeek.org), as well as novel ideas that [leverage and integrate physics]({{< ref "/project/ceds-cps-security.md" >}}) — physical limitations, physical sensor output, and insight into commands sent to control systems — to help monitor and protect networked energy system devices under control.

Recent highlights of Berkeley Lab Computing Sciences' cybersecurity research activities in cybersecurity for energy delivery systems include:

* Development and application of differential privacy to [power grid](https://secpriv.lbl.gov/project/ceds-privacy/) and [vehicle mobility](https://secpriv.lbl.gov/project/csr-private-data/) data and applications &rArr; The DOE Office of [Cybersecurity, Energy Security, and Emergency Response (CESER)](https://www.energy.gov/ceser/office-cybersecurity-energy-security-and-emergency-response) is seeking to deploy the former operationally and the latter has already enabled mobility research otherwise not possible due to data sharing restrictions.

* Developed the first practical approaches to [integrate physics of operational technology in the power grid with intrusion detection]({{< ref "/project/ceds-cps-security.md" >}}) to ensure their secure operation. &rArr; Now broadly used in applied research efforts globally, and appear in DOE funding solicitations and Congressional budget appropriations.

* Developing a technique to [enable automated response to cyberattacks against rooftop solar inverters]({{< ref "/project/ceds-cigar.md" >}}).


### Some recent news:

[Berkeley Lab Leading the Way with New Cybersecurity Projects](https://crd.lbl.gov/news-and-publications/news/2023/berkeley-lab-leading-the-way-with-new-cybersecurity-projects/) — Nov. 6, 2023


#### [Older News](/news)


### Key Representative Publications:

Robert Currie, Sean Peisert, Anna Scaglione, Aram Shumavon, and Nikhil Ravi, "Data Privacy for the Grid: Toward a Data Privacy Standard for Inverter-Based and Distributed Energy Resources," _[IEEE Power & Energy Magazine](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8014)_, 21(5), pp. 58-57, Sept.-Oct 2023.

Raksha Ramakrishna, Anna Scaglione, Tong Wu, Nikhil Ravi, and Sean Peisert, “[Differential Privacy for Class-based Data: A Practical Gaussian Mechanism](https://doi.org/10.48550/arXiv.2306.05578),”
_[IEEE Transactions on Information Forensics and Security](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)_, 23 June 2023.

Robert Currie, Sean Peisert, Anna Scaglione, Aram Shumavon, and Nikhil Ravi, "Data Privacy for the Grid: Toward a Data Privacy Standard for Inverter-Based and Distributed Energy Resources," _[IEEE Power & Energy Magazine](https://magazine.ieee-pes.org)_, 2023.

Nikhil Ravi, Anna Scaglione, Sachin Kadam, Reinhard Gentz, Sean Peisert, Brent Lunghino, Emmanuel Levijarvi, and Aram Shumavon, "[Differentially Private *K*-means Clustering Applied to Meter Data Analysis and Synthesis](https://doi.org/10.1109/TSG.2022.3184252)," _[IEEE Transactions on Smart Grid](https://www.ieee-pes.org/ieee-transactions-on-smart-grid)_, June 17, 2022.

Ciaran Roberts Sy-Toan Ngo, Alexandre Milesi, Sean Peisert, Daniel Arnold, Shammya Saha, Anna Scaglione, Nathan Johnson, Anton Kocheturov, Dmitriy Fradkin, "[Deep Reinforcement Learning for DER Cyber-Attack Mitigation](https://escholarship.org/uc/item/5069z5wn)," _Proceedings of the [IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)](https://sgc2020.ieee-smartgridcomm.org)_, November 11–13, 2020.

<!--
Mahdi Jamei, Raksha Ramakrishna, Teklemariam Tesfay, Reinhard Gentz, Ciaran Roberts, Anna Scaglione, and Sean Peisert, "[Phasor Measurement Units Optimal Placement and Performance Limits for Fault Localization](https://www.cs.ucdavis.edu/~peisert/research/2020-JSAC-PMULocalization)," _[IEEE Journal on Selected Areas in Communications (J-SAC)](https://www.comsoc.org/publications/journals/ieee-jsac)_, _[Special Issue on Communications and Data Analytics in Smart Grid](https://www.comsoc.org/publications/journals/ieee-jsac/cfp/communications-and-data-analytics-smart-grid)_, accepted 2 October, 2019.  \[[DOI](https://doi.org/10.1109/JSAC.2019.2951971)\]
-->

Ciaran Roberts, Anna Scaglione, Mahdi Jamei, Reinhard Gentz, Sean Peisert, Emma M. Stewart, Chuck McParland, Alex McEachern, and Daniel Arnold, "[Learning Behavior of Distribution System Discrete Control Devices for Cyber-Physical Security](https://escholarship.org/uc/item/8hf0c89n)," _[IEEE Transactions on Smart Grid](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5165411)_, accepted 31 July, 2019.  \[[DOI](http://doi.org/10.1109/TSG.2019.2936016)\]

<!--
Melissa Stockman, Dipankar Dwivedi, Reinhard Gentz, Sean Peisert, "[Detecting Programmable Logic Controller Code Using Machine Learning](https://web.cs.ucdavis.edu/~peisert/research/2019-IJCIP-DetectingPLCCode.pdf)," _[International Journal of Critical Infrastructure Protection](https://www.journals.elsevier.com/international-journal-of-critical-infrastructure-protection)_, vol. 26, 100306, September 2019. (accepted July 3, 2019). \[[DOI](https://doi.org/10.1016/j.ijcip.2019.100306)\]
-->

Mahdi Jamei, Anna Scaglione, Ciaran Roberts, Emma Stewart, Sean Peisert, Chuck McParland, and Alex McEachern, "[Anomaly Detection Using μPMU Measurements in Distribution Grids](https://escholarship.org/uc/item/3zf1f06g)," _[IEEE Transactions on Power Systems](https://www.ieee-pes.org/ieee-transactions-on-power-systems)_, 33(4), pp. 3611–3623, October 25, 2017. \[[DOI](https://doi.org/10.1109/TPWRS.2017.2764882)\]

Mahdi Jamei, Emma Stewart, Sean Peisert, Anna Scaglione, Chuck McParland, Ciaran Roberts, and Alex McEachern, "[Micro Synchrophasor-Based Intrusion Detection in Automated Distribution Systems: Towards Critical Infrastructure Security](http://www.escholarship.org/uc/item/84j8f0md)," _[IEEE Internet Computing](http://computer.org/internet/)_," 20(5), pp. 18-27, Sept./Oct. 2016. \[[DOI](http://doi.ieeecomputersociety.org/10.1109/MIC.2016.102)\]

Chuck McParland, Sean Peisert, and Anna Scaglione, "[Monitoring Security of Networked Control Systems: It's the Physics](http://www.escholarship.org/uc/item/8f8738wd.pdf)," _[IEEE Security and Privacy](http://www.computer.org/security)_,**12**(6), November/December 2014. \[[BibTeX](http://www.cs.ucdavis.edu/%7Epeisert/bibtex/Peisert2014-SPMag.bib)\] \[[DOI](http://dx.doi.org/10.1109/MSP.2014.122)\]


### Software

A portion of the software developed through this project can be [downloaded via Github](https://github.com/lbnl-cybersecurity).


### Projects

<!--
Listings of specific projects in [cybersecurity for energy delivery systems](/tags/power-grid/) are available.
-->

