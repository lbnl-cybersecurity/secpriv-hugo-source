+++
title = "Privacy-Preserving Data Analysis for Scientific Discovery"
date = 2023-01-19
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["differential privacy","machine learning","medical","data privacy","research cyberinfrastructure","secure systems","transportation","confidential computing","AI"]

# Project summary to display on homepage.
summary = "This project aims to produce methods, processes, and architectures applicable to a variety of scientific computing domains that enables querying, machine learning, and analysis of data while protecting against releasing sensitive information beyond pre-defined bounds.  It is supported by LBNL CSR funds and is led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/)."

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


## Project Summary

Data is frequently not shared by organizations because that data is considered by the organization to be in some way sensitive. For example, there may be laws or regulations prohibiting sharing due to personal privacy or national security issues, or the organization owning the data may also consider that data to be a proprietary trade secret. In any case, that data cannot or will not be released in raw form, and so alternative approaches are needed if that data is to be shared at all.

Today, data is often not shared at all, or if it is shared, it is done so in ways that require people processing or analyzing that data to access the data in highly secured, non-networked environments set up to prevent any data from being exfiltrated either physically from a building or certainly from a network. This is the reason why much research is hindered.  Sometimes data is shared through processes of "anonymization" in which data is typically either masked or made more general.  Unfortunately, these techniques have repeatedly been shown to fail, typically by merging external information containing identifiable information with quasi-identifiers contained in the dataset in order to identify "anonymized" records in the dataset. 

This project aims to develop a method of leveraging a variety of hardware and software apparoaches, in concert with privacy-preserving technologies, such as differential privacy, for the scientific analysis of sensitive data, in order to provide significantly greater confidence to the owner of a set of sensitive data that the data will not be exposed or altered, and also reduce the liability exposure of the data center to assertions of security negligence or insider attacks by providing an environment in which even they cannot access the raw data, all without significant negative impacts to usability or performance.  The environment that we envision that is is both secure and usable, and also has protections against "insiders" such as system administrators leverages techniques that are relatively new, and just becoming practically useful for these purposes.  

This project is supported by Berkeley Lab Contractor Supported Research funding.

#### Principal Investigator:
[Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) (PI; LBNL)  

#### Senior Personnel

[Chen-nee Chuah][Chuah] \
[Jane Macfarlane][Macfarlane] \
[Michael Zhang][Zhang]


#### Graduate Students

[Ammar Haydari][Ammar]

#### Past Researchers

[Hamdy Elgammal][Elgammal] \
[Reinhard Gentz](https://crd.lbl.gov/divisions/scidata/idf/staff/reinhard-gentz/)  

#### Past Students:

[Archit Garg][Archit] \
[Chitrabhanu Gupta][Gupta] \
[Jinyue Song][Song] \
[Jayneel Vora][Vora]


[Vora]: http://jayneelvora.com
[Gupta]: https://www.linkedin.com/in/chitrabhanu-gupta-6114a8145/
[Archit]: https://www.linkedin.com/in/garchit07/
[Song]: https://www.linkedin.com/in/jinyue-song-17021668/

[Ammar]: https://www.linkedin.com/in/ammarhydr/
[Chuah]: https://crd.lbl.gov/divisions/scidata/idf/affiliates/chen-nee-chuah/
[Elgammal]: https://crd.lbl.gov/divisions/scidata/idf/staff/hamdy-hosny-elgammal/
[Macfarlane]: https://eta.lbl.gov/people/jane-macfarlane
[Zhang]: https://faculty.engineering.ucdavis.edu/zhang/

### Press regarding this project:

[Scientific Data Division Summer Students Tackle Data Privacy](https://crd.lbl.gov/news-and-publications/news/2022/scientific-data-division-summer-students-tackle-data-privacy/) - Sept. 15, 2022

[Summer Students Tackle COVID-19](https://cs.lbl.gov/news-media/news/2020/summer-students-support-covid-19-response) - Oct. 21, 2020

### Publications resulting from this project:

Ammar Haydari, Chen-Nee Chuah, Michael Zhang, Jane Macfarlane, and Sean Peisert, "Differentially Private Map Matching for Mobility Trajectories," _Proceedings of the [2022 Annual Computer Security Applications Conference (ACSAC)](https://www.acsac.org/2022/)_, Austin, TX, December 5-9, 2022.

Hector Garcia Martin, Tijana Radivojevic, Jeremy Zucker, Kristofer Bouchard, Jess Sustarich, Sean Peisert, Dan Arnold, Nathan Hillson, Gyorgy Babnigg, Jose Manuel Marti, Christopher J. Mungall, Gregg T. Beckham, Lucas Waldburger, James Carothers, ShivShankar Sundaram, Deb Agarwal, Blake A. Simmons, Tyler Backman, Deepanwita Banerjee, Deepti Tanjore, Lavanya Ramakrishnan, and Anup Singh, "[Perspectives for Self-Driving Labs in Synthetic Biology](https://arxiv.org/abs/2210.09085)," arXiv preprint [arXiv:2210.09085](https://arxiv.org/abs/2210.09085), 14 Oct 2022.

Ammar Haydari, Michael Zhang, Chen-Nee Chuah, Jane Macfarlane, and Sean Peisert, "[Adaptive Differential Privacy Mechanism for Aggregated Mobility Dataset](https://arxiv.org/abs/2112.08487)," arXiv preprint arXiv:2112.08487, 10 Dec 2021.

Luca Pion-Tonachini, Kristofer Bouchard, Hector Garcia Martin, Sean Peisert, W. Bradley Holtz, Anil Aswani, Dipankar Dwivedi, Haruko Wainwright, Ghanshyam Pilania, Benjamin Nachman, Babetta L. Marrone, Nicola Falco, Prabhat, Daniel Arnold, Alejandro Wolf-Yadlin, Sarah Powers, Sharlee Climer, Quinn Jackson, Ty Carlson, Michael Sohn, Petrus Zwart, Neeraj Kumar, Amy Justice, Claire Tomlin, Daniel Jacobson, Gos Micklem, Georgios V. Gkoutos, Peter J. Bickel, Jean-Baptiste Cazier, Juliane Müller, Bobbie-Jo Webb-Robertson, Rick Stevens, Mark Anderson, Ken Kreutz-Delgado, Michael W. Mahoney, James B. Brown, "[Learning from Learning Machines: a New Generation of AI Technology to Meet the Needs of Science](https://arxiv.org/abs/2111.13786)," arXiv preprint [arXiv:2111.13786](https://arxiv.org/abs/2111.13786), 27 Nov 2021.


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

Sean Peisert, "The Social Dilemma," (panel; with Safiya Noble, UCLA; Gillian Hayes UCI; Bryan Cunningham, UCI; Pegah Parsi, UCSD; and Allison Henry, UC Berkeley), [University of California Data Privacy Day](https://compliance.ucr.edu/data-privacy-day-2022), January 28, 2022.

Keynote: "Usable Computer Security and Privacy to Enable Data Sharing for Scientific Research," [Second International Silicon Valley Cybersecurity Conference (SVCC)](https://svcc2021.svcsi.org/), December 3, 2021.

Sean Peisert, "Advancing Cybersecurity as an Enabling Capability in High-Performance Computing Environments", [HPC User Forum](https://www.hpcuserforum.com/events.html), Sept. 7–9, 2021

Sean Peisert, "Cyber Privacy and Security Risks During the Pandemic” (panel - with Bart Preneel, KU Leuven; Kritika Bhardwaj, NLU Delhi; Margaret Bourdeaux, Harvard/Berkman Klein; Susan Landau, Tufts; and Smitha Prasad, NLU Delhi), Hewlett Foundation event hosted by the [Fletcher School](https://fletcher.tufts.edu/) at Tufts University and the [Centre for Communication Governance (CCG)](https://ccgdelhi.org/) at National Law University, Delhi, December 17, 2020.

Sean Peisert, "Fragility, Interdependence, and Tradeoffs — Cybersecurity and Privacy Lessons from the Pandemic," [Federal Cybersecurity research Interagency Working Group (CSIA IWG)](https://www.nitrd.gov/nitrdgroups/index.php?title=CSIA), [NITRD](https://www.nitrd.gov/), December 3, 2020.

Sean Peisert, "Scientific Computing and Sensitive Data," [DataLab](https://datalab.ucdavis.edu/) [Health Data Science and Systems Research and Learning Cluster](https://datalab.ucdavis.edu/health-data-science-systems/), University of California, Davis, October 2, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis in Scientific Computing Environments," [White House Office of Science & Technology Policy Workshop](https://www.whitehouse.gov/ostp/), Eisenhower Administration Building, Washington, D.C., Jan. 31, 2020.

Sean Peisert, "Privacy-Preserving Data Analysis for Energy Delivery Systems and Scientific Discovery," [Western Area Power Administration (WAPA)](https://www.wapa.gov/), Golden, CO, November 5, 2019.

Sean Peisert, "[Usable Computer Security and Privacy to Enable and Encourage Data Sharing for Scientific Research](http://sites.nationalacademies.org/cs/groups/pgasite/documents/webpage/pga_189637.pdf),"  [National Academies of Sciences, Engineering, and Medicine Committee on Science, Engineering, Medicine, and Public Policy (COSEMPUP) Meeting](http://sites.nationalacademies.org/pga/cosepup/index.htm), Washington, D.C., November 8, 2018.

Sean Peisert, "[Cybersecurity Challenges and Opportunities in High-Performance Computing Environments](https://2018.isc-program.com/?page_id=10&id=inv_sp155&sess=sess126)," [International Supercomputing Conference (ISC)](https://2018.isc-program.com/), Frankfurt, Germany,  June 26, 2018.

More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for research cyberinfrastructure and high-performance computing](/research/research-cyberinfrastructure/).
