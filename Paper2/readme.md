# RESEARCH PAPER 2
#### Paper Title
# Exploring the Security Awareness of the Python and JavaScript Open Source Communities 
Gábor Antal, University of Szeged, Szeged, Hungary
antal@inf.u-szeged.hu
Márton Keleti University of Szeged, Szeged, Hungary
keletim@inf.u-szeged.hu
Péter Hegedűs, MTA-SZTE Research Group on,Artificial Intelligence,Szeged, Hungary
hpeter@inf.u-szeged.hu

## AUTHORS
+ Gabor Antal
+  Peter Hegedus
+  Márton Keleti
**Track** MSR 2020 Mining Challenge
>At the timeMon 29 Jun 2020 12:40 - 13:00 at MSR:Zoom2 - MSR Mining Challenge Chair(s): Antoine Pietri, Stefano Zacchiroli, Diomidis Spinellis

#### Conference (and Link): 
https://2020.msrconf.org/details/msr-2020-mining-challenge/3/Exploring-the-Security-Awareness-of-the-Python-and-JavaScript-Open-Source-Communities

**Paper PDF link**
["Click here to open the paper PDF"](https://arxiv.org/pdf/2006.13652.pdf )

# Introduction
This research is about Exploring Software security awareness of two open-resource communities, Python and JavaScript. AS software security is one of the obvious problrm that , identifies threats that target most software, impacting the security vulnerability on the daily basis. so in this research it will defined how to how to examine vulnerability mitigation. And for this eximination Python and JavaScript open-source projects are being targeted as the both are the most popular and widely used languages in surroundings. On the basis of Software Heritage Graph Dataset containing development history of publically available software it is being find that JavaScript security vulnerability is falling into 87 various catogries whereas Python is falling into 71 catogries out of which 55 security vulnerability are common.
#### Motivation
The basic focus of the ressearch is working on  : What are the typical security vulnerability types the JavaScript and Python open-source communities mitigate and how do they relate to each other? And How quickly the JavaScript and Python open-source communities mitigate a newly published security vulnerability?

# Research Methodology
##### Approach
Heuristics-based approach is used to gather the vulnerability mitigation commits for Python and JavaScript. All the commits are searched on “CVE-”, “CWE-”, “NVD-” patterns by using SQL queries. And the most widely used commits messagess are on CWE identifier. So we first create a temporary table named cve_rev with 357,757 row is created. Then after that Python revision is considered to check as if it must contain the root directory either _init_py or setup. py. python module is project can not be used without it. Same happens with JavaScript revision too , to check it must contain either index.js, app.js, server.js . In the second step 3,718 rows for Python and 4,136 rows for JavaScript are retrieved that are stored in new table named cve_revs_py and cve_revs_js, respectively.
**Tools and Queries for Data Mining :** Python and JavaScripts revision are primed and message committed by CVE/CWE. Commit message can containt same IDs of CVE/CWE for enormous time but only one entry of CVE/CWE is counted once per revision. To focusing on vulnerability types, link the each CVE entries with parallel CWE catogries vulnerabilities. some revision also contained the CWE groups without specifying any perticcular CVE entries.
**Software Heritage Graph Dataset Version :** Software Heritage properly import the dataset into local database with some alterations to the original load script. Size of database is quite large so data importing may take some time even if you are using very high speed hardware.

##### Results and Related work
After the revision work a total 3,458 vulnerability mitigation commits for JavaScript and 2,884 for Python. To which CWE types groups are resolved. From 2015 to 2018 JavaScript vulnerability ratio is growing continuesly whereas  python's vulnerability ratio is quite stable
**i.** Typical Vulnerability issues Types (RQ1): From RQ1 vulnerabulity mitigation commits 103 CWE catogries types are extracted and out of which 55 CWE types are common in both Python and JavaScripts, 32 groups are found in JavaScript and remaining 16 are in Python.
**ii.** Reaction Times to Security Issues (RQ2): In this commit average nmuber of days wearing on between mitigation commit date and publiched date of CVE entry are mentioned. 2010 to 2014 for Pythoon and 2017 for JavaScripts are the peak years for both of comminities to start mitigating vulnerabilities in their code. And if CVE entries never mitigated then it could be good research for future methodology.JavaScript vulnerablitiy reacts fast informationm in CWE 200 type took almost 50days whereas it took 200days in python for CWE type vulnerability.
vulnerability cycle [6,19] helps other to understand the its nature and analyzing the bug prediction. In thids procee  Li et Paxson [8] conduct large-scale empiriacl work with above 4000 patches to find out vulnerability fix life cycle and ccharacterstics. for security identificaton the Xu et al. [24] proposed a binary-level patch analysis framework called SPAIN. Vásquez et al. [23] analyzed 660 Android-related vulnerabilities
and used with both NVDb and Google Andriod security.
##### Threats to validty
Most of the time the mention the CVE IDx explicitly so in that case the actual vulonerability can be  drop its validity. So to nevalute this threat randomly 700 mcommit messages are evaluted from identifier revision.

# Result
The research is being made for exprloring the vulnerability mitigation commits and its identifying types in the Python and JavaScript. 103 different CWE group were detected. It is concluded that JavaScript and Python communities both suffer the most from different types of vulnerabilities. It is observed that different languages have different typical vulnerability catogaries and they can be overlap.