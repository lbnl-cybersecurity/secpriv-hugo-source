+++
title = "Election Process Modeling and Analysis"
date = 2008-10-01
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "elections", "deep-learning"]`
tags = ["formal methods"]

# Project summary to display on homepage.
summary = "This  project looked at defining means for understanding what data can be sanitized, and how.  At LBNL, this project was led by [Sean Peisert](https://www.cs.ucdavis.edu/~peisert/) and was funded by the Institute for Information Infrastructure Protection (I3P)."

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

We have had several different thrusts to our work with elections and electronic voting.

One key thrust was to explore [process composition tools](http://laser.cs.umass.edu/tools/littlejil.shtml) as applied to elections, concentrating particularly on mail-in and Internet voting. This included exploration of how to compose systems from pre-analyzed process components, how to analyze the vulnerability of these systems to attacks, and how to guarantee that important security properties are ensured for the resulting composed system. The underlying processes represent aspects of national and local elections, their composition produces an election process, and analysis of the composition gives insight into potential errors or attacks on the election. Providing an approach for [formally reasoning](http://laser.cs.umass.edu/staticanalysis/index.shtml) about human participation extends current security work. The project also breaks new ground by exploring process-based approaches for modeling and defending against attacks.

Another thrust that we have examined looked at auditing. Election auditing verifies that the systems and procedures work as intended, and that the votes have been counted correctly. If a problem arises, forensic techniques enable auditors to determine what happened and how to compensate if possible. Complicating this is that the audit trails enabling analysis of failures may contain information that either exposes the identity of the voter (enabling voter coercion, for example); or that communicates a message to a third party (enabling vote selling). The goal of this project was to determine the information needed to assess whether the election process in general, and e-voting machines in particular, operate with the desired degree of assurance, especially with respect to anonymity and privacy.

The leads at UC Davis for this work were:

<A HREF="http://nob.cs.ucdavis.edu/bishop/">Matt Bishop</A> (PI; UC Davis) \
<A HREF="http://www.cs.ucdavis.edu/~peisert/">Sean Peisert</A> (CoPI; UC Davis and LBNL)

This work was performed in close cooperation with the <A HREF="http://www.marinvotes.org/">Marin County Registrar of Voters' office</A> and the <A HREF="http://www.yoloelections.org/">Yolo County Clerk-Recorder's office</A>.

We also collaborated closely with <A HREF="http://laser.cs.umass.edu/people/ljo.html">Lee Osterweil</A>, <A HREF="http://www.cs.umass.edu/~clarke/">Lori Clarke</A>, <A HREF="https://www.math.umass.edu/~avrunin">George Avrunin</A>, and their graduate students and postdocs in the <A HREF="http://laser.cs.umass.edu/">LASER Lab</A> at <A HREF="http://www.cs.umass.edu/">UMass Amherst</A>.


More information is available at the [UC Davis elections and electronic voting project web site](https://www.cs.ucdavis.edu/~peisert/projects/voting.html) and [UMass Amherst elections project web site](http://laser.cs.umass.edu/casestudies/elections.shtml).

### Selected publications resulting from this project

Matt Bishop, Philip Stark, Josh Benaloh, Joseph Kiniry, Ron Rivest, Sean Peisert, Joseph Hall, and Vanessa Teague, "<A HREF="https://lawfareblog.com/open-source-software-wont-ensure-election-security">Open-Source Software Won't Ensure Election Security</A>," <A HREF="https://www.lawfareblog.com">Lawfare</A>, August 24, 2017.  [<A HREF="bibtex/Bishop2017-OSS-Elections.bib">bib</A>]

Leon J. Osterweil, Matt Bishop, Heather M. Conboy, Huong Phan, Borislava I. Simidchieva, George S. Avrunin, Lori A. Clarke, and Sean Peisert, "<A HREF="research/2017-TOPS-ElectionProcesses.pdf">A Comprehensive Framework for Using Iterative Analysis to Improve Human-Intensive Process Security: An Election Example</A>," <em><A HREF="http://tops.acm.org">ACM Transactions on Privacy and Security (TOPS)</A></em>, 20(2), March 2017. [<A HREF="http://dx.doi.org/10.1145/3041041">DOI</A>] [<A HREF="http://dl.acm.org/authorize?N23264">OA</A>] [<A HREF="http://www.escholarship.org/uc/item/6r53h7zt">CDL</A>]

Matt Bishop, Heather Conboy, Huong Phan, Borislava I. Simidchieva, George Avrunin, Lori Clarke, Lee Osterweil, and Sean Peisert," <A HREF="research/2014-WRIT-Insider-Process.pdf">Insider Detection by Process Analysis</A>," <EM>Proceedings of the <A HREF="http://www.sei.cmu.edu/community/WRIT2014/">2014 Workshop on Research for Insider Threat (WRIT)</A></EM>, 
<A HREF="http://www.ieee-security.org/TC/SPW2014/">IEEE Computer Society Security and Privacy Workshops</A>, San Jose, CA, May 18, 2014.


Matt Bishop and Sean Peisert, "<A HREF="research/2012-SandP-ElectionsSecurity.pdf">Security and Elections</A>,"
<em><A HREF="http://www.computer.org/security">IEEE Security and Privacy</A></em>,<strong>10</strong>(5), pp. 64&ndash;67, Sept.-Oct. 2012. [<A HREF="bibtex/Peisert2012-SP.bib">BibTeX</A>] [<A HREF="http://dx.doi.org/10.1109/MSP.2012.127">DOI</A>]

Huong Phan, George Avrunin, Matt Bishop, Lori Clarke, and Leon J. Osterweil, "<A HREF="https://www.usenix.org/system/files/conference/evtwote12/evtwote12-final26.pdf">A Systematic Process-Model-Based Approach for Synthesizing Attacks and Evaluating Them</A>," <EM>Proceedings of the <A HREF="http://www.usenix.org/events/evtwote12/">2012 Electronic Voting Technology Workshop/Workshop on Trustworthy Elections (EVT/WOTE)</A></EM>, Washinton, D.C., August 2012.


Borislava I. Simidchieva, Sophie J. Engle, Michael Clifford, Alicia Clay Jones, Sean Peisert, Matt Bishop, Lori A. Clarke, and Leon J. Osterweil, "<A HREF="http://www.usenix.org/event/evtwote10/tech/full_papers/Simidchieva.pdf">Modeling Faults to Improve Election Process Robustness</A>,"
<EM>Proceedings of the <A HREF="http://www.usenix.org/events/evtwote10/">2010 Electronic Voting Technology Workshop/Workshop on Trustworthy Elections (EVT/WOTE)</A></EM>, 
Washinton, D.C., August 11&ndash;13, 2010.  [<A HREF="bibtex/Peisert2010-EVT.bib">BibTeX</A>] [<A HREF="http://www.usenix.org/events/evtwote10/tech/full_papers/Simidchieva.pdf">Authoritative</A>]

Matt Bishop, Sean Peisert, Candice Hoke, Mark Graff, and David Jefferson, "<A HREF="research/2009-EVT-Forensics-BPHGJ.pdf">E-Voting and Forensics: Prying Open the Black Box</A>,"
<EM>Proceedings of the <A HREF="http://www.usenix.org/events/evtwote09/">2009 Electronic Voting Technology Workshop/Workshop on Trustworthy Elections (EVT/WOTE)</A></EM>,  Montreal, Canada, August 10&ndash;11, 2009. [<A HREF="bibtex/Peisert2009-EVT.bib">BibTeX</A>] [<A HREF="http://www.usenix.org/event/evtwote09/tech/full_papers/bishop.pdf">Authoritative</A>]

Sean Peisert, Matt Bishop, and Alec Yasinsac, "<A HREF="research/2009-PBY-HICSS-Voting.pdf">Vote Selling, Voter Anonymity, and Forensic Logging of Electronic Voting Machines</A>," <em>Proceedings of the <A HREF="http://www.hicss.hawaii.edu/hicss_42/apahome42.htm">42nd Hawaii International Conference on System Sciences (HICSS)</A></em>, Decision Technologies and Service Sciences Track, <A HREF="http://www.hicss.hawaii.edu/hicss_42/minitracks/st-dfp.htm">Digital Forensics Pedagogy and Foundational Research Activity Minitrack</A>, 
Waikoloa, HI, January 5&ndash;8, 2009. <em><strong>(Nominated for Best Paper Award)</strong></em> [<A HREF="bibtex/Peisert2008-HICSS.bib">BibTeX</A>] [<A HREF="http://dx.doi.org/10.1109/HICSS.2009.503">DOI</A>]

Matt Bishop, Mark Graff, Candice Hoke, David Jefferson, and Sean Peisert, "<A HREF="research/electionofficialtechguide-2008-10-08.pdf">Resolving the Unexpected in Elections: Election Officials' Options</A>," October 8, 2008. [<A HREF="bibtex/EE2008.bib">BibTeX</A>] [<A HREF="http://www.escholarship.org/uc/item/4xb8p2jn">CDL</A>]</DD>
<DD>Distributed by the <A HREF="http://www.electionexcellence.org/">Center For Election Excellence</A> and the <A HREF="http://www.americanbar.org/">American Bar Association</A>.


<em>Sponsors:</em> <A HREF="http://www.nsf.gov/">National Science Foundation</A> <A HREF="http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=0905503">CCF-0905503</A>, <A HREF="http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1049738">CNS-1049738</A>, <A HREF="http://www.nsf.gov/awardsearch/showAward.do?AwardNumber=1258577">CNS-1258577</A>, and <A HREF="http://www.nist.gov/itl/vote/">NIST</A>


More information is available on other Berkeley Lab research projects focusing on [cybersecurity](/projects/) in general, as well as specifically on [cybersecurity for research cyberinfrastructure and high-performance computing](/research/research-cyberinfrastructure/).
