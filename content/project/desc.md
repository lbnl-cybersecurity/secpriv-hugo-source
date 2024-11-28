+++
title = "Data Enclaves for Scientific Computing"
date = 2023-01-30
draft = false
profile = false
show_date = false

aliases = [
  "/project/ascr-secure-edge"
]

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["HPC","network","research cyberinfrastructure","secure systems","confidential computing","edge","nuclear treaty assurance"]

# Project summary to display on homepage.
summary = "This project will develop secure computation architectures to ensure trustworthiness of scientific data while addressing the gaps left by existing solutions for scientific workflows to address the specific power, performance, and usability, and needs from the edge to the HPC center. It is led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/), [Venkatesh Akella]( https://faculty.engineering.ucdavis.edu/akella/), and [Jason Lowe-Power](https://faculty.engineering.ucdavis.edu/lowepower/)."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

featured = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


#### Principal Investigators:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) \
[Venkatesh Akella][Akella] \
[Jason Lowe-Power][Lowe-Power]   

#### Research Staff:
[Farzad Fatollahl-Fard](https://crd.lbl.gov/farzad-fatollahi-fard/) \
[Dr. Paul Hargrove](https://crd.lbl.gov/paul-hargrove/)

#### Affiliated Graduate Students:
[Kaustav Goswami](https://sites.google.com/view/kaustavgoswami) ([UC Davis](https://www.cs.ucdavis.edu))  

#### Past Researchers:
[Ayaz Akram][Akram] ([UC Davis](https://www.cs.ucdavis.edu) / LBNL) 

[Kaustav]: https://sites.google.com/view/kaustavgoswami
[Lowe-Power]: https://faculty.engineering.ucdavis.edu/lowepower/
[Akella]: https://faculty.engineering.ucdavis.edu/akella/
[Akram]: http://www.ayazakram.com

Scientific data today is at risk due to how it is collected, stored, and analyzed in highly disparate computing systems.  We believe that in order to solve the problems described above that future HPC hardware and software solutions should be co-designed together with security and scientific computing integrity concepts designed and built into as much of the stack from the outset as possible. 



<!--
Advanced wireless networking is here, and with it, the continuation of an extremely rapid proliferation of network-connected devices. In the scientific world, this includes computational systems, sensor networks, and industrial control devices, designed to enable closed-loop automation of the scientific cyberinfrastructure involved in data and experiments. This proliferation of connectivity will introduce new vulnerabilities with each new device connected.

A key risk due to this increased vulnerability is the trustworthiness of data collected at the edge. While controls used to ensure security in the face of today’s threats, including even nation states, may be suffcient within the perimeters of HPC facilities, the risk of tampering with and theft of U.S. scientific intellectual property grows exponentially outside those facilities because traditional physical controls are no longer available for devices deployed in the field.
-->

This project is developing new architectures appropriate to the performance and usage needs of scientific computing to secure scientific data from the edge to the HPC center.  This includes includes sensor and edge systems that collect and process of that data takes place outside protection boundaries of traditional HPC centers, including against attacks such as ransomware and physical attacks against the computing system. Our approach will address the gaps left by existing solutions for scientific workflows to address the specific power, performance, and usability, and needs from the edge to the HPC center.

This project is supported by the US Department of Energy's Office of Science's [Advanced Scientific Computing Research (ASCR)](http://science.energy.gov/ascr/) program under the following grants:

"[Toward a Hardware/Software Co-Design Framework for Ensuring the Integrity of Exascale Scientific Data]( "/project/ascr-hpc-cybersecurity-codesign/")," PI: Sean Peisert, 2015.

"Cybersecurity for Edge-to-Center Scientific Computing in Advanced Wireless Environments," PI: Sean Peisert, Co-PIs: Venkatesh Akella and Jason Lowe-Power, 2021.

It is also funded by [NNSA DNN](https://www.energy.gov/nnsa/nonproliferation) research:

"Data Enclaves for Secure Computing (DESC): Enabling Secure Nuclear Treaty Verification in Hostile Environments," PI: Sean Peisert, Co-PIs: Venkatesh Akella, David Archer, and Jason Lowe-Power, 2024.

It is also funded by LBNL Contractor Supported Research.

See also the [hardware-software security page](https://arch.cs.ucdavis.edu/projects/security) at [DArchR, the UC Davis Architecture Research group](https://arch.cs.ucdavis.edu).

### Press regarding this project:

[Berkeley Lab Cybersecurity Specialist Highlights Data Sharing Benefits, Challenges at NAS Meeting](https://cs.lbl.gov/news-media/news/2018/berkeley-lab-cybersecurity-expert-highlights-data-sharing-at-national-academies-meeting/) — Dec. 4, 2018

[CRD's Peisert to Discuss Data Sharing at National Academies' COSEMPUP Meeting](https://today.lbl.gov/2018/11/05/crds-sean-peisert-to-discuss-data-sharing-at-national-academies-cosempup-meeting-on-nov-8/) — Nov. 5, 2018

[Lab Experts Help Coordinate ISC18, World’s First, Largest Computing Conference](http://today.lbl.gov/2018/06/26/lab-experts-help-coordinate-isc18-worlds-first-largest-computing-conference/) - June 21, 2018


### Publications resulting from this project:

Ayaz Akram, Venkatesh Akella, Sean Peisert, and Jason Lowe-Power, “[SoK: Limitations of Confidential Computing via TEEs for High-Performance Compute Systems](https://doi.org/10.1109/SEED55351.2022.00018),” _Proceedings of the [2022 IEEE International Symposium on Secure and Private Execution Environment Design (SEED)](https://seed22.engr.uconn.edu)_, Sept. 26–27, 2022.

Ayaz Akram, Venkatesh Akella, Sean Peisert, and Jason Lowe-Power, "[Enabling Design Space Exploration for RISC-V Secure Compute Environments](https://arch.cs.ucdavis.edu/security/simulation/2021/06/11/gem5-tee.html)," _Proceedings of the [Fifth Workshop on Computer Architecture Research with RISC-V (CARRV)](https://carrv.github.io/2021/)_, (co-located with [ISCA 2021](https://iscaconf.org/isca2021/)) June 17, 2021

Sean Peisert, "[Trustworthy Scientific Computing](https://cacm.acm.org/magazines/2021/5/252168-trustworthy-scientific-computing/fulltext)," [_Communications of the ACM (CACM)_](https://cacm.acm.org), 64(5), pp. 18–21, May 2021.

Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on General Purpose TEEs](https://arch.cs.ucdavis.edu/security/2021/05/17/hpc-tee-performance.html)," _[Proceedings of the 35th IEEE International Parallel & Distributed Processing Symposium (IPDPS)](http://www.ipdps.org)_, May 17–21, 2021.

Ayaz Akram, "[Trusted Execution for High-Performance Computing](http://www.ayazakram.com/papers/eurodw.pdf)," _[Proceedings of the 15th EuroSys Doctoral Workshop (EuroDW)](https://eurodw21.github.io)_, 2021. [video](https://www.youtube.com/watch?v=7CLwftj1_Hs)

Ayaz Akram, "[Architectures for Secure High-Performance Computing](http://www.ayazakram.com/papers/yarch.pdf)," _[Proceedings of the Young Architect Workshop (YArch)](https://sites.gatech.edu/yarch2021/)_ held in conjunction with the International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), April 2021. [video](https://www.youtube.com/watch?v=cvL37bn04IQ)


Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on Trusted Execution Environments](https://arxiv.org/abs/2010.13216)," arXiv preprint arXiv:2010.13216, 25 Oct 2020.

### Presentations:

<!--
"[Hardware/Software Co-Design to Enable Trustworthy Data Domains for HPC](https://custom.cvent.com/DCBD4ADAAD004096B1E4AD96F3C8049E/files/event/f64a4f28b4734808924cc8c3d9a2af63/cb841a4cdcb64b0eb8b1cc53a4a42208.pdf)"
Ayaz Akram, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, [DOE ASCR Workshop on Reimagining Codesign](https://web.cvent.com/event/f64a4f28-b473-4808-924c-c8c3d9a2af63/summary), March 16-18, 2021. \[[White Paper](https://custom.cvent.com/DCBD4ADAAD004096B1E4AD96F3C8049E/files/event/f64a4f28b4734808924cc8c3d9a2af63/5fef554c8ff84d8283de212addcaf446.pdf)\]
-->

Sean Peisert, "Trustworthy Scientific Cyberinfrastructure," [NASEM Cyber Resilience Forum Summer 2023 Meeting](https://www.nationalacademies.org/event/40436_08-2023_summer-2023-meeting-of-the-forum-on-cyber-resilience), San Francisco, CA, August 31, 2023.

Keynote: "Usable Computer Security and Privacy to Enable Data Sharing in High-Performance Computing Environments," [3rd High-Performance Computing Security Workshop, NIST National Cybersecurity Center of Excellence (NCCoE)](https://www.nist.gov/news-events/events/2023/03/3rd-high-performance-computing-security-workshop), Rockville, MD, March 16, 2023. [NIST IR 8476 Workshop Report](https://csrc.nist.gov/pubs/ir/8476/final)

Keynote: "Usable Computer Security and Privacy to Enable Data Sharing in High-Performance Computing Environments," [Interdisciplinary Symposium on Responsible Innovation: Intersection of Privacy and Artificial Intelligence, Center for Data Science and AI Research (CeDAR)](https://cedar.ucdavis.edu/events/california-data-protection-and-privacy-day), University of California, Davis, March 10, 2023.

"Responsible Innovation at the Intersection of Privacy and Artificial Intelligence (AI),” (panel; with Eric Dang, Darci Sears, moderators; Tom Kemp, and Richard Arney) [Interdisciplinary Symposium on Responsible Innovation: Intersection of Privacy and Artificial Intelligence, Center for Data Science and AI Research (CeDAR)](https://cedar.ucdavis.edu/events/california-data-protection-and-privacy-day), University of California, Davis, March 10, 2023.

"Securing Edge-to-Center Computing with Trustworthy Data Domains," [Monterey Data Workshop](https://www.montereydataconference.org/workshop-2022), April 21, 2022.

Sean Peisert, “Cybersecurity and Privacy research for Science and Energy,” [Networking and Information Technology Research and Development (NITRD) Cyber Security and Information Assurance (CSIA) Interagency Working Group (IWG)](https://www.nitrd.gov/coordination-areas/csia/) Meeting, March 24, 2022.

Sean Peisert, "Securing Edge-to-Center Computing with Trustworthy Data Domains," [2022 AFRL/AFOSR/DOE Energy Cost of Information Workshop](https://community.apan.org/wg/afosr/w/researchareas/31786/2022-energy-consequences-of-information-workshop/), February 18, 2022.

Venkatesh Akella and Sean Peisert, "Usable Computer Security and Privacy to Enable Data Sharing for Scientific Research," [Trusted Computing Center of Excellence (TCCOE) Summit](https://hopin.com/events/tccoe-2022-summit%22), February 1–3, 2022.

Keynote: "Usable Computer Security and Privacy to Enable Data Sharing for Scientific Research," [Second International Silicon Valley Cybersecurity Conference (SVCC)](https://svcc2021.svcsi.org/), December 3, 2021.

Sean Peisert, "Advancing Cybersecurity as an Enabling Capability in High-Performance Computing Environments", [HPC User Forum](https://www.hpcuserforum.com/events.html), Sept. 7–9, 2021

Sean Peisert, "Cyber Privacy and Security Risks During the Pandemic” (panel - with Bart Preneel, KU Leuven; Kritika Bhardwaj, NLU Delhi; Margaret Bourdeaux, Harvard/Berkman Klein; Susan Landau, Tufts; and Smitha Prasad, NLU Delhi), Hewlett Foundation event hosted by the [Fletcher School](https://fletcher.tufts.edu/) at Tufts University and the [Centre for Communication Governance (CCG)](https://ccgdelhi.org/) at National Law University, Delhi, December 17, 2020.

Sean Peisert, "Fragility, Interdependence, and Tradeoffs — Cybersecurity and Privacy Lessons from the Pandemic," [Federal Cybersecurity research Interagency Working Group (CSIA IWG)](https://www.nitrd.gov/nitrdgroups/index.php?title=CSIA), [NITRD](https://www.nitrd.gov/), December 3, 2020.

Sean Peisert, "Scientific Computing and Sensitive Data," [DataLab](https://datalab.ucdavis.edu/) [Health Data Science and Systems Research and Learning Cluster](https://datalab.ucdavis.edu/health-data-science-systems/), University of California, Davis, October 2, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis in Scientific Computing Environments," [White House Office of Science & Technology Policy Workshop](https://www.whitehouse.gov/ostp/), Eisenhower Administration Building, Washington, D.C., Jan. 31, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis for Energy Delivery Systems and Scientific Discovery," [Western Area Power Administration (WAPA)](https://www.wapa.gov/), Golden, CO, November 5, 2019.

Ayaz Akram and Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, Sean Peisert, "[Using Trusted Execution Environments on High Performance Computing Platforms](https://arch.cs.ucdavis.edu/security/2019/07/25/hpc-enclaves.html),"
 [Open-Source Enclaves Workshop (OSEW 2019)](https://keystone-enclave.org/open-source-enclaves-workshop/), Berkeley, CA, July 25, 2019.

Sean Peisert, "[Usable Computer Security and Privacy to Enable and Encourage Data Sharing for Scientific Research](http://sites.nationalacademies.org/cs/groups/pgasite/documents/webpage/pga_189637.pdf),"  [National Academies of Sciences, Engineering, and Medicine Committee on Science, Engineering, Medicine, and Public Policy (COSEMPUP) Meeting](http://sites.nationalacademies.org/pga/cosepup/index.htm), Washington, D.C., November 8, 2018.

Sean Peisert, "[Cybersecurity Challenges and Opportunities in High-Performance Computing Environments](https://2018.isc-program.com/?page_id=10&id=inv_sp155&sess=sess126)," [International Supercomputing Conference (ISC)](https://2018.isc-program.com/), Frankfurt, Germany,  June 26, 2018.

### Other Resources:

Ayaz Akram, [Setting up Trusted HPC System in the Cloud](https://arch.cs.ucdavis.edu/blog/2020-11-19-cloud-hpc), November 19, 2020.


More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for research cyberinfrastructure and high-performance computing](/research/research-cyberinfrastructure/).
