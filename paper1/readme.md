# RESEARCH PAPER 1
#### Paper Title

# Employing Contribution and Quality Metrics for Quantifying the Software Development Process
***Themistoklis Diamantopoulos, Michail D. Papamichail, Thomas Karanikiotis Kyriakos C. Chatzidimitriou, and Andreas L. Symeonidis
  (thdiaman,mpapamic,thomas.karanikiotis,kyrcha)
     @issel.ee.auth.gr,asymeon@eng.auth.gr Electrical and Computer Engineering Dept., Aristotle University of Thessaloniki Thessaloniki, Greece***

## AUTHORS

|Authors| Site|    
|-----------|------|
|Themistoklis DiamantopouloS|[Open](https://2020.msrconf.org/profile/themistoklisdiamantopoulos)|
|Michail Papamichail|[Open](https://2020.msrconf.org/profile/michailpapamichail)|
|Thomas Karanikiotis|[Open](https://2020.msrconf.org/profile/thomaskaranikiotis)|
|Kyriakos Chatzidimitriou|[Open](https://2020.msrconf.org/profile/kyriakoschatzidimitriou)|
|Andreas Symeonidis|[Open](https://2020.msrconf.org/profile/andreassymeonidis)|



>**Track:**  [MSR 2020 Data Showcase](https://2020.msrconf.org/track/msr-2020-Data-showcase?track=MSR%20Data%20Showcase)

>**At the time:** Tue 30 Jun 2020 10:52 - 11:00 at MSR:Zoom - 
Quaility Evolution ***Chair(s): Jürgen Cito***

#### Conference (and Link):
 https://2020.msrconf.org/details/msr-2020-Data-showcase/7/Employing-Contribution-and-Quality-Metrics-for-Quantifying-the-Software-Development-P

**Paper PDF link**
["Click here to open the papr PDF"](https://issel.ee.auth.gr/wp-content/uploads/2020/05/MSR2020.pdf )

# Introduction
 This research paper is about the Collaborative work of employeeqs and their measurement for software development values. AS software development is arising rapidly and become a collaborative process of taking part in online hosting programming services. ***For Example:*** Github , Bitbucket or Gitlab. Developers are doing collective work as software engineering is providing enormous facilities. __Github__ is a repository hosting services, it is providing web graphical interface , access control and collaborative features. In these collaborative materials , software projects are the combinations of different contribution. This collaboration is a multiple axes having so many things from coding a project to its debugging process, it includes each and  every information. Thus all the data combine and form a **"story"** of all project containing answers of every ___W.H Question___.
 #### Motivation
The basic motive of the research is the dataset of monitoring what we call the ***story*** of the project consider as ***Agile Methodoloy*** having goal of building high quality software. The ***Github*** infrastructure examines all the data contribution. Sum-up the employees contibutions and quality measurement that answer every arising question.



# Research Methodology
#### Architecture And Tools
The architecture of this platform is involving four given below modules.
 ***__i Data Downloader :__*** It is a Python application that uses all the GitHUb repository to fetch all the offered information. This information contain issues, comments, issue commits, issues events, repository information, contributors information and the source code repository as well.
***__ii. MangoDB Management :__*** It is used as the database management system, having all the raw data repossess from GitHub accompanying results of contribution and quantity analysis. Data are arranged in collection icdicating different types of information. for more afficient data the files of information are connected through elements like repository name, commit etc.
***__iii. Contributor Analyzer :__*** It uses the information retrieved from GitHub in order to enumerates a series of measure that quantify the activity of each contributor in terms of both, development and operations. The logic behind the selection of these metrics derives from their use in current research [9, 12, 15, 16, 20] from a development and operations standpoint.
 ***__iv. Quality Analyzer__*** Effectual tracking of the software development process needs analyzing the quality of the final product. so for overall evolution of product's lifecycle , statical analysis on weekly basis is being performed to recognize  the generally accepted coding implementation.

![ Architectuere Overview](./Arch_view.jpg) 

#### DATASET And Construction
In software development process the online repository comprises vital part. constituting serial provocation and providing list of chances that are swamp to the accessible data to enable and compute the software development to form a worthwhile rise model. these data are inhabiting in GitHub to form a dataset, used for that objective. It also contain some challenges given below :
***i .*** Which project to Analyze: Creating dataset for wrapping the huge range of different synopsis in which about 3,000 project are being analyzed to reveal projects's all information (popularity, complexity, number, size,contribution, duration.
***ii .*** Which metric  to compute: Software development is a superficial task that involves the parameter essential for deliberation. These parameters are discrete characterstics involving project's work, tendency, contribution,collaberation. well in this process contributor can also change within the roles  of project.
***iii .*** Enable tailor-made dataset construction: The main target of the whole scenario is that to impart the dataset that is formable enough to used by researcher to tangled vast range of queries. The frameworks of both, repositories and contributions are enabled to refine data based on sole need and objectives of each researcher.

#### Impact And Research Direction
This dataset can be used to square up to the various challenges in research methodology. As it contain various software process metrics with instant of infraction. So the developers manner can be analyzed in various axes. Such as debugging, commit issues comment distribution and contribution metrics. The dataset include source code, textual and process data that can be excavate to take out the areas of expertise for each developers. so that it will help developers to manage their profile and find best team match. Research in field of automated bug assignment is very wide and use in many metrics of this dataset.

# Result
The research is being made for the excavate contribution data from GitHub that gives useful insights on software development process and produce practical result that may be used to upgrade it. This research turn out the area for building the useful metrics. The dataset in this research is providing facility to answer the various research queries.

