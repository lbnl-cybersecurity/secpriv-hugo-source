+++
# Projects widget.
widget = "portfolio"
headless = true
active = true
date = 2016-04-20T00:00:00

title = "Cybersecurity for Scientific and High-Performance Computing"
subtitle = ""

# Order that this section will appear in.
weight = 50

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
#view = 1


[content]
  page_type = "project"

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "project"

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
  filter_default = 0

 [[content.filter_button]]
   name = "HPC"
   tag = "scientific-computing"


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

Berkeley Lab [Computing Sciences Research][CRD] is an active participant in a number of projects in the arena of security for scientific, high-performance computing systems and high-bandwidth research and education networks.  Research sponsors have typically included [DOE's ASCR](https://science.energy.gov/ascr/) program, and the [National Science Foundation (NSF)][NSF]  [SaTC](https://www.nsf.gov/funding/pgm_summ.jsp?from=fund&orgAbbr=NSF&pims_id=504709) program and [OAC](https://www.nsf.gov/div/index.jsp?div=OAC) office, among others.  

[CRD]: https://crd.lbl.gov

[ASCR]: https://science.osti.gov/ascr/
[CEDS R&D]: https://www.energy.gov/ceser/activities/cybersecurity-critical-energy-infrastructure/cybersecurity-research-development-and
[DOE]: https://www.energy.gov
[NSA]: https://www.nsa.gov
[NNSA]: https://nnsa.energy.gov
[NSF]: https://www.nsf.gov

Berkeley Lab's cybersecurity goals are to research, develop, evaluate, adapt, and integrate advanced security and privacy solutions that enable or improve scientific workflows that may otherwise not be possible due to real or perceived security restrictions that, using today's solution, impose onerous usability and/or performance constraints, thereby hindering scientific progress.

Berkeley Lab has had a leadership role in security in scientific computing environments for many years, including the development of the [Zeek (Bro) Network Security Monitor](https://www.zeek.org), the [100G performance enhancements of Zeek (Bro)](https://commons.lbl.gov/display/cpp/100G+Intrusion+Detection), and Zeek (Bro)'s commercial spin-off, [Corelight, Inc.](https://www.corelight.com/), as well as leading several DOE-sponsored activities related to defining a cybersecurity research program within the DOE Office of Science.  <!--More recently, Berkeley Lab led the coordination of the ["Cyber R&D" Enterprise Cyber Capability (ECC)](http://ijc3.lbl.gov) of the DOE-wide Integrated Joint Cybersecurity Coordination Center (iJC3) — a sponsored R&D program involving ten DOE National Laboratories as performers.-->  Berkeley Lab is a co-lead of [Trusted CI, the NSF Cybersecurity Center of Excellence]({{< ref "/project/nsf-trustedci.md" >}}).

Recent highlights of Berkeley Lab Computing Sciences' cybersecurity R&D activities in research cyberinfrastructure include:

* Leading studies into [scientific data integrity](http://hdl.handle.net/2022/24910), [scientific data confidentiality](https://escholarship.org/uc/item/7cz7m1ws), and [software assurance in science](https://blog.trustedci.org/2021/12/publication-of-trusted-ci-guide-to.html), [operational technology in science](https://blog.trustedci.org/2022/01/announcing-2022-trusted-ci-annual.html), and [building security into NSF Major Facilities by design](https://blog.trustedci.org/2023/01/announcing-2023-trusted-ci-annual.html).  &rArr; The latter is directly impacting design, construction, and operations of the [California Coastal Research Vessel](https://scripps.ucsd.edu/news/uc-san-diego-receives-35-million-state-funding-new-california-coastal-research-vessel), the NSF [Regional Class Research Vessels](https://ceoas.oregonstate.edu/regional-class-research-vessel-rcrv), [U.S. Antarctic Program’s](https://www.usap.gov/) [$1B icebreaker](https://www.nsf.gov/news/news_summ.jsp?cntn_id=305919&org=OPP), and [Ocean Observatory Initiatives](https://oceanobservatories.org/)’ replacement of hundreds of underwater autonomous vehicles.

* Developed definitions and R&D roadmaps for [hardware/software co-design of future HPC systems](https://secpriv.lbl.gov/project/ascr-hpc-cybersecurity-codesign/), high-throughput networks, and networked scientific instruments to build cybersecurity in by design. &rArr; Led directly to HPC cybersecurity elements of DOE funding solicitations and has been central to [NIST HPC Security working group](https://csrc.nist.gov/projects/high-performance-computing-security).

* Development of [secure computation architectures]({{< ref "/project/desc.md" >}}) optimized for scientific computing to ensure trustworthiness of scientific data from the edge to the HPC center.

* Development and application of differential privacy to [power grid](https://secpriv.lbl.gov/project/ceds-privacy/) and [vehicle mobility](https://secpriv.lbl.gov/project/csr-private-data/) data and applications &rArr; The DOE Office of [Cybersecurity, Energy Security, and Emergency Response (CESER)](https://www.energy.gov/ceser/office-cybersecurity-energy-security-and-emergency-response) is seeking to deploy the former operationally and the latter has already enabled mobility research otherwise not possible due to data sharing restrictions.

* Co-leading the *[Open Science Cyber Risk Profile (OSCRP)](http://trustedci.github.io/OSCRP/)* working group --- an approach to help research cyberinfrastructure operators understand cyber risks. &rArr; Now a recommended reference in all [NSF CICI solicitations](https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=505159) since 2018 and the [NSF Research Infrastructure Guide (RIG) (21-107, Dec. 2021)](https://www.nsf.gov/publications/pub_summ.jsp?ods_key=nsf21107).

* Codification of the “[Medical Science DMZ](http://jamia.oxfordjournals.org/content/23/6/1199.article-info)” — a “network design pattern” for enabling secure, high-volume, high-throughput transfer of sensitive data, such as data subject to HIPAA or CUI regulations. &rArr; Now used by companies and research institutions globally, including  the NSF [Global Research Platform](https://www.theglobalresearchplatform.net/).



<!--
* Development of techniques detecting misuse of high-performance computing resources using both [on-system]({{< ref "/project/ascr-ids-hpc.md" >}}) and [off-system]({{< ref "/project/inferring-computing.md" >}}) side channels.

* Development of a research roadmap for [co-designing high-performance computing systems with security built in]({{< ref "/project/ascr-hpc-cybersecurity-codesign.md" >}}).
-->

### DOE Cybersecurity Workshops and Reports

[ASCR Cybersecurity for Scientific Computing Workshop](https://www.orau.gov/integrity2015/), June 2–3, 2015 \[[report](http://science.osti.gov/~/media/ascr/pdf/programdocuments/docs/ASCR_Cybersecurity_20_Research_Pathways_and_Ideas_Workshop.pdf)\]

[ASCR Cybersecurity Workshop](http://www.orau.gov/cybersecurity2015/), January 7–9, 2015 \[[report](http://science.osti.gov/~/media/ascr/pdf/programdocuments/docs/ASCR_Cybersecurity_For_Scientific_Computing_Integrity_Report_2015.pdf), [news](/news-and-publications/news/2015/peisert-compiles-workshop-report-on-securing-scientific-computing-integrity/)\]

[DOE Grassroots Cybersecurity Initiative](https://wiki.cac.washington.edu/display/doe/Home), 2008–2010 \[[Frincke presentation](https://science.osti.gov/~/media/ascr/ascac/pdf/meetings/feb08/Frincke_presentation.pdf), [Catlett ASCAC presentation,](https://science.osti.gov/~/media/ascr/ascac/pdf/meetings/mar09/Catlett.pdf) [report 1](https://science.osti.gov/~/media/ascr/pdf/program-documents/docs/Cyber_security_science_dec_2008.pdf), [report 2](https://science.osti.gov/~/media/ascr/pdf/program-documents/docs/Complex_networked_systems_program_final.pdf), [report 3](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.470.776&rep=rep1&type=pdf)\]

[DOE Cybersecurity R&D Challenges for Open Science: Developing a Roadmap and Vision,](https://web.archive.org/web/20080724104302/http://www.dsd.lbl.gov/Workshops/CyberWorkshop) January 24–26, 2007 \[[news](https://web.archive.org/web/*/http://dsd.lbl.gov/Workshops/CyberWorkshop/), [report](http://www.osti.gov/scitech/biblio/923678-wbxW3Y/)\]


### Some recent news:

[Announcing publication of the Operational Technology Procurement Vendor Matrix](https://blog.trustedci.org/2023/12/announcing-publication-of-operational.html) — Dec. 15, 2023

[Updates on Trusted CI’s Efforts in Cybersecurity by Design of NSF Academic Maritime Facilities](https://blog.trustedci.org/2023/07/updates-on-trusted-cis-efforts-in.html) — Jul. 24, 2023

[SAVE THE DATE: Announcing the 2023 NSF Cybersecurity Summit, Oct 24-26, 2023 in Berkeley, CA](https://blog.trustedci.org/2023/03/save-date-announcing-2023-nsf.html) — Mar. 21, 2023

[Registration Open for 3rd HPC Security Workshop at NIST NCCoE](https://blog.trustedci.org/2023/02/register-NIST-3rd-HPC-workshop.html) — Feb. 3, 2023

[Announcing the 2023 Trusted CI Annual Challenge: Building Security Into NSF Major Facilities By Design](https://blog.trustedci.org/2023/01/announcing-2023-trusted-ci-annual.html) — Jan. 25, 2023

Sean Peisert, [Publication of the Trusted CI Roadmap for Securing Operational Technology in NSF Scientific Research](https://blog.trustedci.org/2022/11/publication-of-trusted-ci-roadmap-for.html) — Nov. 16, 2022.

Sean Peisert, [Open Science Cyber Risk Profile (OSCRP) Updated with Science DMZ, Software Assurance, Operational Technology, and Cloud Computing Elements](https://blog.trustedci.org/2022/11/open-science-cyber-risk-profile-oscrp.html) — Nov. 1, 2022

[Findings of the 2022 Trusted CI Study on the Security of Operational Technology in NSF Scientific Research](https://blog.trustedci.org/2022/07/findings-of-2022-trusted-ci-study-on.html) — July 15, 2022

[Berkeley Lab’s Sean Peisert Tapped to Take on Deputy Director Role](https://cs.lbl.gov/news-media/news/2022/berkeley-labs-sean-peisert-tapped-to-take-on-deputy-director-role/) — June 28, 2022

[Better Scientific Software (BSSw) Helps Promote Trusted CI Guide to Securing Scientific Software](https://blog.trustedci.org/2022/05/better-scientific-software-bssw-helps.html) — May 13, 2022

[Announcing the 2022 Trusted CI Annual Challenge on Scientific OT/CPS Security](https://blog.trustedci.org/2022/01/announcing-2022-trusted-ci-annual.html) - Jan. 5, 2022


#### [Older News](/news)

### Key Representative Publications:

Andrew Adams, Dan Arnold, Jeannette Dopheide, Ryan Kiser, Mark Krenz, Drew Paine, Sean Peisert, Michael Simpson, and John Zage, "[Trusted CI Operational Technology Procurement Vendor Matrix](https://zenodo.org/doi/10.5281/zenodo.10257812)," Dec. 14, 2023. DOI: 10.5281/zenodo.10257813

Jim Basney, Sean Peisert, Scott Russell, Kelli Shute, Bart Miller, and Kathy Benninger, "[A Vision for Securing NSF's Essential Scientific Cyberinfrastructure - Trusted CI Five-Year Strategic Plan (2024-2029)](https://doi.org/10.5281/zenodo.8193607)," August 1, 2023.

Ammar Haydari, Chen-Nee Chuah, Michael Zhang, Jane Macfarlane, and Sean Peisert, "Differentially Private Map Matching for Mobility Trajectories," _Proceedings of the [2022 Annual Computer Security Applications Conference (ACSAC)](https://www.acsac.org/2022/)_, Austin, TX, December 5-9, 2022.

Andrew Adams, Emily K. Adams, Dan Gunter, Ryan Kiser, Mark Krenz, Sean Peisert, and John Zage. “[Roadmap for Securing Operational Technology in NSF Scientific Research](https://doi.org/10.5281/zenodo.7327987),” [Trusted CI Report](https://doi.org/10.5281/zenodo.7327987), November 16 2022. 

Ayaz Akram, Venkatesh Akella, Sean Peisert, and Jason Lowe-Power, “SoK: Limitations of Confidential Computing via TEEs for High-Performance Compute Systems,” _Proceedings of the [2022 IEEE International Symposium on Secure and Private Execution Environment Design (SEED)](https://seed22.engr.uconn.edu)_, Sept. 26–27, 2022.

<!--
Emily K. Adams, Daniel Gunter, Ryan Kiser, Mark Krenz, Sean Peisert, Susan Sons, and John Zage, "[Findings of the 2022 Trusted CI Study on the Security of Operational Technology in NSF Scientific Research](https://doi.org/10.5281/zenodo.6828675)," [Trusted CI Report](https://doi.org/10.5281/zenodo.6828675), July 13, 2022.
-->

Andrew Adams, Kay Avila, Elisa Heymann, Mark Krenz, Jason R. Lee, Barton Miller, and Sean Peisert, "[Guide to Securing Scientific Software](https://doi.org/10.5281/zenodo.5777646)," [Trusted CI Report](https://doi.org/10.5281/zenodo.5777646), December 14, 2021.

Sean Peisert, "[Trustworthy Scientific Computing](https://cacm.acm.org/magazines/2021/5/252168-trustworthy-scientific-computing/fulltext)," _[Communications of the ACM (CACM)](https://cacm.acm.org/)_, 64(5), pp. 18–21, May 2021.

Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on General Purpose TEEs](https://arch.cs.ucdavis.edu/papers/2021-5-17-hpc-tee-performance)," _[Proceedings of the 35th IEEE International Parallel & Distributed Processing Sysmposium (IPDPS)](http://www.ipdps.org)_, May 17–21, 2021.

<!--
Ayaz Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power, and Sean Peisert, "[Performance Analysis of Scientific Computing Workloads on Trusted Execution Environments](https://arxiv.org/abs/2010.13216)," arXiv preprint arXiv:2010.13216, 25 Oct 2020.
-->

<!--
Bogdan Copos and Sean Peisert, "[Catch Me If You Can: Using Power Analysis to Identify HPC Activity](https://arxiv.org/abs/2005.03135)," arXiv preprint arXiv:2005.03135, 2020.
-->

Sean Peisert, Eli Dart, William K. Barnett, James Cuff, Robert L. Grossman, Edward Balas, Ari Berman, Anurag Shankar, and Brian Tierney, "[The Medical Science DMZ: An Network Design Pattern for Data-Intensive Medical Science](https://academic.oup.com/jamia/article/25/3/267/4367749)", _Journal of the American Medical Informatics Association (JAMIA)_, 25,(3):267–274, March 2018.

Sean Peisert, "[Security in High-Performance Computing Environments](https://cacm.acm.org/magazines/2017/9/220422-security-in-high-performance-computing-environments/fulltext)", _[Communications of the ACM (CACM)](https://cacm.acm.org/)_, 60(9):72-80, September 2017.

Sean Peisert, Von Welch, Andrew Adams, Michael Dopheide, Susan Sons, RuthAnne Bevier, Rich LeDuc, Pascal Meunier, Stephen Schwab, and Karen Stocks, Ilkay Altintas, James Cuff, Reagan Moore, and Warren Raquel, "[Open Science Cyber Risk Profile](http://trustedci.github.io/OSCRP/OSCRP.html)," February 2017.

Sean Whalen, Sean Peisert, Matt Bishop, "[Multiclass Classification of Distributed Memory Parallel Computations](http://www.escholarship.org/uc/item/6mq830qz)," _[Pattern Recognition Letters (PRL)](http://www.journals.elsevier.com/pattern-recognition-letters/)_, 34(3):322-329, February 2013.

<!--
Sean Whalen, Sophie Engle, Sean Peisert, Matt Bishop, "[Network-Theoretic Classification of Parallel Computation Patterns](http://www.escholarship.org/uc/item/0g3653gc)," _[International Journal of High Performance Computing Applications (IJHPCA)](https://journals.sagepub.com/home/hpc)_, 26(2):159-169, May 2012.
-->

### Projects

<!--
Listings of specific projects in [security for high-performance computing](/tags/hpc) and [security for scientific networking](/tags/network) are available.
-->
