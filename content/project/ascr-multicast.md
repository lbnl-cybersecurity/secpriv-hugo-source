+++
title = "Reliable Multicast for Continuous Data Transmission for Nuclear Treaty Verification"
date = 2002-09-30
draft = false
profile = false
show_date = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine learning", "deep-learning"]`
tags = ["nuclear treaty assurance", "network", "secure systems", "cryptography"]

# Project summary to display on homepage.
summary = "This project examined the use of reliable multicast communication protocols, including for the Comprehensive test Ban Treaty."

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

LBNL's work in reliable multicast built on graduate work in developing reliable multicast by Agarwal (Totem), Berket (InterGroup),  Keith Jackson, and Artur Muratas.  Related to this work included implementation of a secure group protocol, and improving methods for securing group keys.

One of LBNL's efforts in reliable multicast involved working groups created to set up the Comprehensive Nuclear-Test-Ban Treaty verification network, an international network connecting 321 monitoring stations around the world. The goal was to monitor in real-time whether there were activities that could be the result of nuclear weapon testing.   LBNL's role in the project examined the feasibility of using multicast in the Comprehensive Nuclear Test-Ban Treaty Organization (CTBTO) network, monitoring for signs of explosions. 

Subseqeuntly, LBNL also used reliable multicast to provide remote experiment access to Advanced Light Source (ALS) Beamline 7.

Later, Chevassut led a team including Agarwal, Essiari, Farret, and Thompson on secure group multicast communication encryption.

The work at LBNL was funded primarily by DOE ASCR. 

#### Principal Investigators and Senior Personnel:
[Deb Agarwal](https://dst.lbl.gov/~deba/) \
[Karlo Berket](https://dblp.org/pid/14/2773.html) \
[Olivier Chevassut](https://dblp.org/pid/86/4171.html) \
[Abdelilah Essiari](https://crd.lbl.gov/divisions/scidata/sustainable-software-engineering/staff/abdelilah-essiari/) \
[Guillaume Farret](https://www.linkedin.com/in/guillaume-farret/?originalSubdomain=it) \
[Keith R. Jackson](https://dblp.org/pid/64/6863.html) \
[William Johnston](https://www.linkedin.com/in/bill-johnston-69a25014/) \
[Artur Muratas](https://www.linkedin.com/in/artur-muratas-8b4b8521/) \
[Mary R. Thompson](https://www.linkedin.com/in/mary-thompson-320354172/)

#### Collaborators:

Giuseppe Ateniese \
Emmanuel Bresson \
Pierre-Alain Fouque \
Pierrick Gaudry \
Damian Hasse \
Yongdae Kim \
Samuel Meder \
David Pointcheval \
Frank Siebenlist \
Gene Tsudik

### Selected publications resulting from this project:

Michel Abdalla, Emmanuel Bresson, Olivier Chevassut, Bodo Möller, David Pointcheval, "[Strong password-based authentication in TLS using the three-party group Diffie-Hellman protocol](https://core.ac.uk/download/pdf/21751490.pdf)," _Int. J. Secur. Networks_, 2(3/4):284-296, 2007.

Emmanuel Bresson, Olivier Chevassut, and David Pointcheval, "[A security solution for IEEE 802.11's ad hoc mode: password-authentication and group Diffie-Hellman key exchange](https://escholarship.org/uc/item/1s82w7fp)," _Int. J. Wirel. Mob. Comput._, 2(1), 4-13, 2007.

Emmanuel Bresson, Olivier Chevassut, David Pointcheval, "[Provably secure authenticated group Diffie-Hellman key exchange](https://dl.acm.org/doi/pdf/10.1145/1266977.1266979)," _ACM Trans. Inf. Syst. Secur._, 10(3), 2007.

Michel Abdalla, Emmanuel Bresson, Olivier Chevassut, Bodo Möller, David Pointcheval, "[Provably secure password-based authentication in TLS](https://escholarship.org/uc/item/46b4r7g8)," _Proceedings of AsiaCCS_, 2006.

Olivier Chevassut, Pierre-Alain Fouque, Pierrick Gaudry, and David Pointcheval. "[The twist-augmented technique for key exchange]()" _Proceedings of the International Workshop on Public Key Cryptography_, 2006.

Michel Abdalla, Emmanuel Bresson, Olivier Chevassut, David Pointcheval, "[Password-Based Group Key Exchange in a Constant Number of Rounds](https://www.iacr.org/archive/pkc2006/39580436/39580436.pdf)," Public Key Cryptography, 2006.

Michel Abdalla, Olivier Chevassut, Pierre-Alain Fouque, David Pointcheval, [A Simple Threshold Authenticated Key Exchange from Short Secrets](https://www.iacr.org/archive/asiacrypt2005/566/566.pdf), _Proceedings of ASIACRYPT_, 2005.

Michel Abdalla, Olivier Chevassut, David Pointcheval, [One-Time Verifier-Based Encrypted Key Exchange](https://iacr.org/archive/pkc2005/33860048/33860048.pdf). Public Key Cryptography, 2005.

Olivier Chevassut, Pierre-Alain Fouque, Pierrick Gaudry, and David Pointcheval, "[Key derivation and randomness extraction](https://eprint.iacr.org/2005/061.pdf)" Cryptology ePrint Archive 2005.

Emmanuel Bresson, Olivier Chevassut, Abdelilah Essiari, David Pointcheval,
[Mutual authentication and group key agreement for low-power mobile devices](https://www.sciencedirect.com/science/article/pii/S0140366404001987?casa_token=DLfthO8vsSgAAAAA:36YksJWq4GCgLPliyvKL-J1by3rtf-U4u9fj7rqe-Pf0bcEWPIg5QB6YYKS-nY95yi_LqL1pNkY), _Comput. Commun._ 27(17):1730-1737, 2004.

Emmanuel Bresson, Olivier Chevassut, David Pointcheval, [New Security Results on Encrypted Key Exchange](https://www.di.ens.fr/david.pointcheval/Documents/Papers/2004_pkc.pdf), Public Key Cryptography, 2004.

Liang Fang, Samuel Meder, Olivier Chevassut, and Frank Siebenlist, "[Secure password-based authenticated key exchange for web services](https://escholarship.org/content/qt8rj6z0p3/qt8rj6z0p3_noSplash_54d0b4b85ca1b5700d30ac37de93728a.pdf), _Proceedings of the 2004 Workshop on Secure Web Service_, 2004.

Emmanuel Bresson, Olivier Chevassut, David Pointcheval, [Security proofs for an efficient password-based key exchange](https://eprint.iacr.org/2002/192.ps), _Proceedings of CCS_, 2003.

Emmanuel Bresson, Olivier Chevassut, Abdelilah Essiari, David Pointcheval, [Mutual Authentication and Group Key Agreement for low-Power Mobile Devices](http://www.di.ens.fr/~pointche/Documents/Papers/2004_jcc.pdf), _Proceedings of MWCN_, 2003

Karlo Berket, Deborah A Agarwal, and Olivier Chevassut. [A practical approach to the InterGroup protocols](https://www.osti.gov/servlets/purl/836659). _Future Generation Computer Systems_, 18(5):709–719, 2002.

Emmmanuel Bresson, Olivier Chevassut, and David Pointcheval, "[Group Diffie-Hellman Key Exchange Secure Against Dictionary Attacks](https://www.iacr.org/cryptodb/archive/2002/ASIACRYPT/45/45.pdf)," _Proceedings of ASIACRYPT_, Queenstown, New Zealand, 2002.

Emmanuel Bresson, Olivier Chevassut, and David Pointcheval. "[Dynamic group Diffie-Hellman key exchange under standard assumptions](https://escholarship.org/content/qt4c64w97m/qt4c64w97m.pdf)," _Proceedings of Eurocrypt_, Amsterdam, Netherlands, 2002

Olivier Chevassut, "[Authenticated group Diffie-Hellman key exchange: theory and practice](https://escholarship.org/content/qt0pm199fp/qt0pm199fp.pdf)," 2002.

Emmanuel Bresson, Olivier Chevassut, and David Pointcheval. "[The group Diffie-Hellman problems](https://www.osti.gov/servlets/purl/801967-nETruB/native/)," _Selected Areas in Cryptography: 9th Annual International Workshop_, 2002.

Emmanuel Bresson, Olivier Chevassut, David Pointcheval, [Security Proofs for an Efficient Password-Based Key Exchange](https://eprint.iacr.org/2002/192.ps). IACR Cryptol. ePrint Arch. 2002.

Deborah A. Agarwal. [Discussion Of Reliable Multicast Deployment Progress For The Continuous Data Protocol](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.106.8499&rep=rep1&type=pdf). In _Proceedings of the 23rd Annual DoD/DOE Seismic Research Review: Worldwide Monitoring of Nuclear Explosions_, Jackson Hole, WY, Oct. 2001.

Deborah A Agarwal, Olivier Chevassut, Mary R Thompson, and Gene Tsudik. [An integrated solution for secure group communication in wide-area networks](https://www.osti.gov/servlets/purl/780589). In _Proceedings of the Sixth IEEE Symposium on Computers and Communications_, pages 22–28, 2001.

Emmanuel Bresson, Olivier Chevassut, and David Pointcheval, "[Provably Authenticated Group Diffie-Hellman Key Exchange - The Dynamic Case](https://iacr.org/archive/asiacrypt2001/22480292.pdf)," _Proceedings of ASIACRYPT_, 2001.

Emmanuel Bresson, Olivier Chevassut, David Pointcheval, Jean-Jacques Quisquater,
[Provably authenticated group Diffie-Hellman key exchange](https://iacr.org/archive/asiacrypt2001/22480292.pdf), _Proceedings of CCS], 2001.

Deborah Agarwal, Richard Stead, Brian Coan, James E Burns, Nishith Shah, and Nicholas Kyriakopoulos. [Initial results of the CD-1 reliable multicast experiment](https://escholarship.org/content/qt40x3788h/qt40x3788h.pdf). Lawrence Berkeley National Laboratory, 2000.

Giuseppe Ateniese, Olivier Chevassut, Damian Hasse, Yongdae Kim, and Gene Tsudik, [The design of a group key agreement API](https://scholar.archive.org/work/emrbgw2gi5cphavtv7u5fvrogu/access/wayback/http://www-users.cs.umn.edu:80/~kyd/paper/achkt99.pdf). _Proceedings of the DARPA Information Survivability Conference and Exposition (DISCEX)_, 2000

Deborah A Agarwal. [Using multicast in the global communications infrastructure for group communication](https://www.osti.gov/servlets/purl/767536). Lawrence Berkeley National Laboratory, 1999.


More information is available on other Berkeley Lab R&D projects focusing on [cybersecurity](/projects/).
