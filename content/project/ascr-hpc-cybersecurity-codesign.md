+++
title = "Toward a Hardware/Software Co-Design Framework for Ensuring the Integrity of Exascale Scientific Data"
date = 2016-09-15
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["HPC","network","machine learning","scientific computing","secure systems","confidential computing"]

# Project summary to display on homepage.
summary = "This project takes a broad look at several aspects of security and scientific integrity issues in HPC systems. It is funded by DOE ASCR and is led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/)."

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


#### Principal Investigator:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI)  

#### Senior Personnel:
[Venkatesh Akella][Akella] ([UC Davis](http://www.cs.ucdavis.edu) / LBNL Faculty Scientist)  
[Jason Lowe-Power][Lowe-Power] ([UC Davis](http://www.cs.ucdavis.edu) / LBNL Faculty Scientist)  

#### LBNL-Affiliated Graduate Students:
[Ayaz Akram][Akram] ([UC Davis](http://www.cs.ucdavis.edu)  / LBNL)  


#### Project Alumni:
[Bogdan Copos](https://sites.google.com/a/ucdavis.edu/bogdancopos/) (LBNL/[UC Davis](http://www.cs.ucdavis.edu); Ph.D. 2017) → SRI International  →  Google   
[Prof. Hein Meling](https://crd.lbl.gov/divisions/scidata/idf/affiliates/hein-meling/) (LBNL/[University of Stavanger](http://www.ux.uis.no/~meling/))   
[Amir Teshome Wonjiga](https://crd.lbl.gov/divisions/scidata/idf/affiliates/amir-teshome-wonjiga/) (LBNL/[INRIA Rennes](https://www.inria.fr/en/centre/rennes); Ph.D. 2019)   
[Reinhard Gentz](https://crd.lbl.gov/divisions/scidata/idf/staff/reinhard-gentz/) (LBNL)   
[Anna Giannakou](https://crd.lbl.gov/divisions/scidata/idf/staff/anna-giannakou/) (LBNL)   


[Lowe-Power]: https://faculty.engineering.ucdavis.edu/lowepower/
[Akella]: https://faculty.engineering.ucdavis.edu/akella/
[Akram]: http://www.ayazakram.com


Scientific data today is at risk due to how it is collected, stored, and analyzed in highly disparate computing systems. How can we make claims about the integrity of data as it traverses open, international networks and via instruments and systems with widely varying reliability and provenance? Numerous causes for integrity loss are possible, including bugs in existing computational pipelines, network events, user error, unintentional system effects or even intentional attack by outsiders (e.g., scientific competitors), insiders (e.g., disgruntled employees), or in the hardware/software supply chain, without any trace of the modification. Given these gaps and shortcomings in existing HPC solutions, how can we make claims about the integrity of the scientific data as it traverses those systems and networks?  
  
We believe that in order to solve the problems described above that future HPC hardware and software solutions should be co-designed together with security and scientific computing integrity concepts designed and built into as much of the stack from the outset as possible. Given the risk of data loss due to software and hardware, this should take into account hardware elements, operating systems, compilers, application software, and the networking stack, all the way down to the way in which software developers write software and users interact with systems in a way that can affect scientific computing integrity. However, prior to laying out the research roadmap to design and construct such an architecture, we believe that several important aspects first need to be understood more clearly.  
  
This project takes a broad look at several aspects of security and scientific integrity issues in HPC systems. Using several case studies as exemplars, and working closely with both domain scientists as well as facility staff, we propose to test and validate several initial concepts in existing scientific computing workflows at NERSC DOE HPC facility, and analyze those models better characterize integrity-related computational behavior.

Early work on this project focused on a range of activities, including identifying misuse of computing systens, leveraging blockchains for scientific computing.  More recent work has focused on developing trustworthy scientific computing architectures.  

For more on the current work, see [Data Enclaves for Scientific Computing](/project/desc/).

This project is supported by the US Department of Energy's Office of Science's [Advanced Scientific Computing Research (ASCR)](http://science.energy.gov/ascr/) program.

### Press regarding this project:


[Berkeley Lab Cybersecurity Specialist Highlights Data Sharing Benefits, Challenges at NAS Meeting](https://cs.lbl.gov/news-media/news/2018/berkeley-lab-cybersecurity-expert-highlights-data-sharing-at-national-academies-meeting/) — Dec. 4, 2018

[CRD's Peisert to Discuss Data Sharing at National Academies' COSEMPUP Meeting](https://today.lbl.gov/2018/11/05/crds-sean-peisert-to-discuss-data-sharing-at-national-academies-cosempup-meeting-on-nov-8/) — Nov. 5, 2018

[Lab Experts Help Coordinate ISC18, World’s First, Largest Computing Conference](http://today.lbl.gov/2018/06/26/lab-experts-help-coordinate-isc18-worlds-first-largest-computing-conference/) - June 21, 2018

[Into the Medical Science DMZ](https://sciencenode.org/feature/into-the-science-dmz.php) (Science Node) March 23, 2018

[Berkeley Lab Researchers Contribute to Making Blockchains Even More Robust](https://cs.lbl.gov/news-media/news/2018/berkeley-lab-researchers-contribute-to-making-blockchains-even-more-robust/) — January 30, 2018

[ESnet's Science DMZ Design Could Help Transfer, Protect Medical Research Data](/news-and-publications/news/2017/esnets-science-dmz-design-could-help-transfer-protect-medical-research-data/) (Science Node) — October 16, 2017

[Berkeley Lab's cybersecurity expert Sean Peisert discusses challenges & opportunities of securing HPC](https://twitter.com/LBNLcs/status/900819240734920704) — Aug. 24, 2017

[HPC security article in Communications of the ACM](https://cacm.acm.org/magazines/2017/9/220422-security-in-high-performance-computing-environments/fulltext)

[Video accompanying HPC security article on Vimeo](https://vimeo.com/226955144)

### Publications resulting from this project:


Ayaz Akram, Venkatesh Akella, Sean Peisert, and Jason Lowe-Power, "Enabling Design Space Exploration for RISC-V Secure Compute Environments," _Proceedings of the [Fifth Workshop on Computer Architecture Research with RISC-V (CARRV)](https://carrv.github.io/2021/)_, (co-located with [ISCA 2021](https://iscaconf.org/isca2021/)) June 17, 2021

Sean Peisert, "[Trustworthy Scientific Computing](https://cacm.acm.org/magazines/2021/5/252168-trustworthy-scientific-computing/fulltext)," [_Communications of the ACM (CACM)_](https://cacm.acm.org), 64(5), pp. 18–21, May 2021.

Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on General Purpose TEEs](https://arch.cs.ucdavis.edu/papers/2021-5-17-hpc-tee-performance)," _[Proceedings of the 35th IEEE International Parallel & Distributed Processing Sysmposium (IPDPS)](http://www.ipdps.org)_, May 17–21, 2021.

Ayaz Akram, "[Trusted Execution for High-Performance Computing](http://www.ayazakram.com/papers/eurodw.pdf)," _[Proceedings of the 15th EuroSys Doctoral Workshop (EuroDW)](https://eurodw21.github.io)_, 2021. [video](https://www.youtube.com/watch?v=7CLwftj1_Hs)

Ayaz Akram, "[Architectures for Secure High-Performance Computing](http://www.ayazakram.com/papers/yarch.pdf)," _[Proceedings of the Young Architect Workshop (YArch)](https://sites.gatech.edu/yarch2021/)_ held in conjunction with the International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), April 2021. [video](https://www.youtube.com/watch?v=cvL37bn04IQ)


Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on Trusted Execution Environments](https://arxiv.org/abs/2010.13216)," arXiv preprint arXiv:2010.13216, 25 Oct 2020.


Ross Gegan, Christina Mao, Dipak Ghosal, Matt Bishop, and Sean Peisert, "[Anomaly Detection for Science DMZs Using System Performance Data](https://escholarship.org/uc/item/2zh6z3vx)," _Proceedings of the [2020 IEEE International Conference on Computing, Networking and Communications (ICNC 2020)](http://www.conf-icnc.org/2020/)_, Big Island, HI, February 17–20, 2020.

Amir Teshome Wonjiga, Louis Rilling, Christine Morin, and Sean Peisert, "[Blockchain as a Trusted Component in Cloud SLA Verification](https://escholarship.org/uc/item/2r60s6b5)," _Proceedings of the [International Workshop on Cloud, IoT and Fog Security (CIFS)](http://cifs.servicelaboratory.ch/)_, co-located with the 12th IEEE/ACM International Conference on Utility and Cloud Computing (UCC), Auckland, New Zealand, December 2–5, 2019.

Amir Teshome Wonjiga, _[User-Centric Security Monitoring in Cloud Environments](https://tel.archives-ouvertes.fr/tel-02570591/file/WONJIGA_Amir.pdf)_. PhD dissertation,  Inria Rennes – Bretagne Atlantique, May 2019.  (Dissertation Advisors: Christine Morin and Louis Rilling)

Anna Giannakou, Daniel Gunter, and Sean Peisert, "[Flowzilla: A Methodology for Detecting Data Transfer Anomalies in Research Networks](https://escholarship.org/uc/item/8f49q4nx),"
_Proceedings of the [5th Innovate the Network for Data-Intensive Science (INDIS) Workshop](https://scinet.supercomputing.org/workshop/sc18-program)_,
Dallas, TX, November 11, 2018.

Sean Peisert, Eli Dart, William K. Barnett, James Cuff, Robert L. Grossman, Edward Balas, Ari Berman, Anurag Shankar, and Brian Tierney, "[The Medical Science DMZ: An Network Design Pattern for Data-Intensive Medical Science](http://dx.doi.org/10.1093/jamia/ocx104)," [_Journal of the American Medical Informatics Association (JAMIA)_](http://jamia.oxfordjournals.org), 25(3):267-274, March 2018.  
  
Sean Peisert, "[Security in High-Performance Computing Environments,"](https://cacm.acm.org/magazines/2017/9/220422-security-in-high-performance-computing-environments/fulltext) [_Communications of the ACM (CACM)_](https://cacm.acm.org), 60(9):72–80, September 2017.

Bogdan Copos, [_Modeling Systems Using Side Channel Information_](https://escholarship.org/uc/item/1xb249zt). PhD dissertation, University of California, Davis, 2017.  (Dissertation Advisor: Sean Peisert)

Sean Peisert, William K. Barnett, Eli Dart, James Cuff, Robert L. Grossman, Edward Balas, Ari Berman, Anurag Shankar, and Brian Tierney, "[The Medical Science DMZ](http://dx.doi.org/10.1093/jamia/ocw032)," [_Journal of the American Medical Informatics Association (JAMIA)_](http://jamia.oxfordjournals.org), 23(6), Nov. 1, 2016.


### Software resulting from this project:

[Blockchain Based Remote Data Integrity Checking Tool](https://github.com/lbnl-cybersecurity/hpc_data_integrity_code)


### Presentations:

<!--
"[Hardware/Software Co-Design to Enable Trustworthy Data Domains for HPC](https://custom.cvent.com/DCBD4ADAAD004096B1E4AD96F3C8049E/files/event/f64a4f28b4734808924cc8c3d9a2af63/cb841a4cdcb64b0eb8b1cc53a4a42208.pdf)"
Ayaz Akram, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, [DOE ASCR Workshop on Reimagining Codesign](https://web.cvent.com/event/f64a4f28-b473-4808-924c-c8c3d9a2af63/summary), March 16-18, 2021. \[[White Paper](https://custom.cvent.com/DCBD4ADAAD004096B1E4AD96F3C8049E/files/event/f64a4f28b4734808924cc8c3d9a2af63/5fef554c8ff84d8283de212addcaf446.pdf)\]
-->

Sean Peisert, "Securing Edge-to-Center Computing with Trustworthy Data Domains," [2022 AFRL/AFOSR/DOE Energy Cost of Information Workshop](https://community.apan.org/wg/afosr/w/researchareas/31786/2022-energy-consequences-of-information-workshop/), February 18, 2022.

Venkatesh Akella and Sean Peisert, "Usable Computer Security and Privacy to Enable Data Sharing for Scientific Research," [Trusted Computing Center of Excellence (TCCOE) Summit](https://hopin.com/events/tccoe-2022-summit%22), February 1–3, 2022.

Keynote: "Usable Computer Security and Privacy to Enable Data Sharing for Scientific Research," [Second International Silicon Valley Cybersecurity Conference (SVCC)](https://svcc2021.svcsi.org/), December 3, 2021.

Sean Peisert, "Advancing Cybersecurity as an Enabling Capability in High-Performance Computing Environments", [HPC User Forum](https://www.hpcuserforum.com/events.html), Sept. 7–9, 2021

Sean Peisert, "Cyber Privacy and Security Risks During the Pandemic” (panel - with Bart Preneel, KU Leuven; Kritika Bhardwaj, NLU Delhi; Margaret Bourdeaux, Harvard/Berkman Klein; Susan Landau, Tufts; and Smitha Prasad, NLU Delhi), Hewlett Foundation event hosted by the [Fletcher School](https://fletcher.tufts.edu/) at Tufts University and the [Centre for Communication Governance (CCG)](https://ccgdelhi.org/) at National Law University, Delhi, December 17, 2020.

Sean Peisert, "Fragility, Interdependence, and Tradeoffs — Cybersecurity and Privacy Lessons from the Pandemic," [Federal Cybersecurity R&D Interagency Working Group (CSIA IWG)](https://www.nitrd.gov/nitrdgroups/index.php?title=CSIA), [NITRD](https://www.nitrd.gov/), December 3, 2020.

Sean Peisert, "Scientific Computing and Sensitive Data," [DataLab](https://datalab.ucdavis.edu/) [Health Data Science and Systems Research and Learning Cluster](https://datalab.ucdavis.edu/health-data-science-systems/), University of California, Davis, October 2, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis in Scientific Computing Environments," [White House Office of Science & Technology Policy Workshop](https://www.whitehouse.gov/ostp/), Eisenhower Administration Building, Washington, D.C., Jan. 31, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis for Energy Delivery Systems and Scientific Discovery," [Western Area Power Administration (WAPA)](https://www.wapa.gov/), Golden, CO, November 5, 2019.


Ayaz Akram and Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, Sean Peisert, "[Using Trusted Execution Environments on High Performance Computing Platforms](https://arch.cs.ucdavis.edu/papers/2019-7-25-hpc-enclaves),"
 [Open-Source Enclaves Workshop (OSEW 2019)](https://keystone-enclave.org/open-source-enclaves-workshop/), Berkeley, CA, July 25, 2019.

Sean Peisert, "[Usable Computer Security and Privacy to Enable and Encourage Data Sharing for Scientific Research](http://sites.nationalacademies.org/cs/groups/pgasite/documents/webpage/pga_189637.pdf),"  [National Academies of Sciences, Engineering, and Medicine Committee on Science, Engineering, Medicine, and Public Policy (COSEMPUP) Meeting](http://sites.nationalacademies.org/pga/cosepup/index.htm), Washington, D.C., November 8, 2018.

Sean Peisert, "[Cybersecurity Challenges and Opportunities in High-Performance Computing Environments](https://2018.isc-program.com/?page_id=10&id=inv_sp155&sess=sess126)," [International Supercomputing Conference (ISC)](https://2018.isc-program.com/), Frankfurt, Germany,  June 26, 2018.

Sean Peisert, "[Keynote: Cybersecurity for HPC Systems: State of the Art and Looking to the Future](https://www.nist.gov/news-events/events/2018/03/high-performance-computing-security-workshop)," [High-Performance Computing Security Workshop](https://www.nist.gov/news-events/events/2018/03/high-performance-computing-security-workshop), National Institute of Standards and Technology (NIST), Gaithersburg, MD, March 28, 2018,

Sean Peisert, "[Security in High Performance Computing Environments](https://bids.berkeley.edu/events/security-and-privacy-data-intensive-high-performance-computing-contexts)," Computing Sciences/NERSC Security Seminar, Lawrence Berkeley National Laboratory, October 5, 2017,

Sean Peisert, "[Security and Privacy in Data-Intensive, High-Performance Computing Contexts](https://bids.berkeley.edu/events/security-and-privacy-data-intensive-high-performance-computing-contexts)," [Berkeley Institute for Data Science (BIDS)](https://bids.berkeley.edu/), University of California, Berkeley, October 2, 2017,

Lee Beausoleil (NSA), David Lombard (Intel), Angelos Keromytis (DARPA), **Sean Peisert** (LBNL), "Panel: HPC Monitoring," [NSCI: High-Performance Computing Security Workshop](https://www.nist.gov/news-events/events/2016/09/nsci-high-performance-computing-security-workshop), National Institute of Standards and Technology (NIST), Gaithersburg, MD, September 30, 2016,

Sean Peisert, [Security Expert on Why HPC Matters - Cybersecurity for HPC Systems: Challenges and Opportunities,](https://www.nist.gov/news-events/events/2016/09/nsci-high-performance-computing-security-workshop) [NSCI: High-Performance Computing Security Workshop](https://www.nist.gov/news-events/events/2016/09/nsci-high-performance-computing-security-workshop), National Institute of Standards and Technology (NIST), Gaithersburg, MD, September 29, 2016,

### Other Resources:


Ayaz Akram, [Setting up Trusted HPC System in the Cloud](https://arch.cs.ucdavis.edu/blog/2020-11-19-cloud-hpc), November 19, 2020.


More information is available on other Berkeley Lab R&D projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for scientific and high-performance computing](/research/scientific-computing/).
