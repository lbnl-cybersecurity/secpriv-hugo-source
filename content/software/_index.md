+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
#widget = "custom"
active = true
date = 2018-08-24T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

# Order that this section will appear in.
weight = 60

[sitemap]
priority = 0.8

+++

LBNL's cybersecurity research team has produced a variety of software tools and libraries that are publicly available for use.  A partial listing of selected software is below:

* [CEDS DP K-Means Clustering](https://github.com/lbnl-cybersecurity/CEDSKMeans).  This repository contains the code for the CEDS Data Product K-Means Clustering. 

* [LBNL Physics-Based Intrusion Detection Zeek/Bro Modules](https://github.com/lbnl-cybersecurity/LBNL_Physics_Based_IDS).   
This software contains a set of signatures for use with the Zeek (née Bro) Network Security Monitor that analyze communication with a physical system and compare the effects of that communication with a physical simulation of the device.  This software was originally applied to analyzing attacks on network-connected equipment that controls various functions within the power grid.

* [LBNL DDoS Detection on Science Networks](https://github.com/lbnl-cybersecurity/ddos-detection).   
 This software is a modular detection tool indended to support for monitoring network logs in order to detect denial of service attacks on "research and education" networks that disambiguates such attacks from sustained, high-volume network flows characteristic of large science projects, and referred to as "elephant flows."

* [LBNL Stream-Processing Architecture for Real-time Cyber-physical Security (SPARCS)](https://github.com/lbnl-cybersecurity/sparcs).  
This software extracts data from distribution-level phasor measurement units (PMUs) and power quality meters, and stores SCADA captured over the network using the Zeek (née Bro) Intrusion Detection System, enables a physically distributed, hierarchical processing of that data, stores the data in one or more databases, and provides both software APIs and a graphical, web-based, front-end for inspection of data.  This software ships without the analytics themselves, which are distributed separately.

* Analytics for Stream-Processing Architecture for Real-time Cyber-physical Security (Analytic-SPARCS).
This software is a set of analytics that monitor both power measurements collected by distribution grid phasor measurement units (µPMUs) and SCADA communication in order to detect cyber attacks against equipment located in distribution grid substations. It leverages both the Zeek (née Bro) Network Security Monitor and the LBNL Stream-Processing Architecture for Real-time Cyber-physical Security (SPARCS).  This software is available free of charge for research and development, non-commercial use.   A commercial use license is available from Berkeley Lab.  Please contact Berkeley Lab's Intellectual Property Office at ipo@lbl.gov for more information.

* [Identifying Computational Operations Based on Power Measurements](https://ipo.lbl.gov/lbnl2016-053/).  
This software is an approach for leveraging sensitive power measurements to "fingerprint" or infer computation taking place on computing systems, including high-performance computing systems, by examining patterns in power use.


* [LBNL Disruption Tolerant Key Management Monitoring for Stream-Processing Architecture for Real-time Cyber-physical Security (DTKM-SPARCS)](https://github.com/lbnl-cybersecurity/dtkm-sparcs).  
This software is a set of signatures that monitor the Disruption-Tolerant Key Management protocol developed by PNNL as part of the DOE CEDS program. It leverages both the Zeek/Bro Network Security Monitor and the LBNL Stream-Processing Architecture for Real-time Cyber-physical Security (SPARCS).

* [Research Network Transfer Performance Predictor (netperf-predict)](https://github.com/lbnl-cybersecurity/tstat-dtn-analysis).  
This software containts two sets of analysis routines for predicting the percentage of retransmitted packets on network flows. One directory contains code that applies random forest regression in order to predict the number of retransmitted packets on each flow, operating on timeseries data from the tstat tool, which outputs flow-like data. The second directory also applies a random forest regression and also incorporates a "smoothing" routine that increases accuracy in some situations.

* [Blockchain Based Remote Data Integrity Checking Tool](https://github.com/lbnl-cybersecurity/hpc_data_integrity_code).  
The software is used to perform remote data integrity checking without relying on a single third party. In order to remove the trusted third party our tool uses distributed ledger (Blockchain) technology. The ledger is used to store evidences (in the form of hash values). These values are used as an input in the integrity checking process.
