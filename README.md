# Statistical Genetics and Genetic Epidemiology

## Content

* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Assignments](#assignments)
* [Contacts](#contacts)
* [Delivery of the Learning Module](#delivery-of-the-learning-module)
* [Schedule](#schedule)
* [Requirements](#requirements)
* [Resources](#resources)
  + [Documents](#documents)
  + [Videos](#videos)
* [Folder Structure](#folder-structure)

## Description

This course provides students with the knowledge foundations necessary to conduct statistical analysis of genetic association study data. It features a series of lectures and hands-on coding sessions covering key topics, including fundamental concepts in population genetics, population structure in genetic association studies, quality control in genetic data and genome-wide association studies. The course places strong emphasis on the use of modern computational tools such as PLINK, MEGMA and GRAF-pop, and real-world data applications to preparing students for both academic and applied careers in statistical genetics and genetic epidemiology.

## Learning Outcomes
By the end of the module, participants will be able to:

**Week 1:**
* Understand basic concepts in molecular genetics and common genetic models.
* Distinguish between Mendelian and complex trait inheritance, and grasp general principles of genetic inheritance.
* Learn how genotype data is stored and accessed (e.g., in PLINK), and how to prepare it for downstream analyses such as GWAS and quality control.

**Week 2:**
* Understand fundamental principles of population genetics, including allele frequencies, genetic drift, and Hardy-Weinberg equilibrium.
* Learn about trait aggregation, heritability, and segregation analysis.
* Understand key study designs and statistical models used in genetic association studies, including case-control and regression-based approaches.

**Week 3:**
* Learn how to perform genome-wide association studies (GWAS), including essential quality control procedures, popular software tools, genotype imputation, and multiple testing correction.
* Understand methods for adjusting for population stratification and conducting meta-analyses in GWAS.
  
## Assignments

Participants should review the [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md) for instructions on how to complete assignments in this module.

There are three assignments.

1. [Assignment 1](./02_activities/assignments/Assignment1.md)
2. [Assignment 2](./02_activities/assignments/Assignment2.md)
3. 1. [Assignment 3](./02_activities/assignments/Assignment3.md)

## Contacts

**Questions can be submitted to the #questions channel on Slack**

* Technical Facilitator:
<!--
  * **Thomas Rosenthal** (he/him)  
    [thomas.rosenthal@utoronto.ca](mailto:thomas.rosenthal@utoronto.ca)
-->
* Learning Support Staff:
<!--
  * **James Li** (he/him)  
  [james.zefang.li@gmail.com](mailto:james.zefang.li@gmail.com)
  * **Laura MacKew** (she/her)  
  [lauramackew@gmail.com](mailto:lauramackew@gmail.com)
  * **Niyaz Nazari** (she/her)  
  [niyaz.mnazari@gmail.com](mailto:niyaz.mnazari@gmail.com)
-->


## Delivery of the Learning Module

This module will include live learning sessions and optional, asynchronous work periods. During live learning sessions, the Technical Facilitator will introduce and explain key concepts and demonstrate core skills. Learning is facilitated during this time. Before and after each live learning session, the instructional team will be available for questions related to the core concepts of the module. Optional work periods are to be used to seek help from peers, the Learning Support team, and to work through the assignments in the learning module, with access to live help. Content is not facilitated, but rather this time should be driven by participants. We encourage participants to come to these work periods with questions and problems to work through. 
 
Participants are encouraged to engage actively during the learning module. They key to developing the core skills in each learning module is through practice. The more participants engage in coding along with the instructional team, and applying the skills in each module, the more likely it is that these skills will solidify. 

Each session will consist of slides to introduce topics, live coding to demonstrate the topics, and occasional breakout rooms/live polls to reinforce the topics. The technical facilitator will introduce the concepts through a collaborative live coding session using R and other specialized genetic sofwares. The technical facilitator will upload any live coding files to this repository for participants to revisit under `./04_this_cohort/live_code`. 

## Schedule 

* Week 1 will focus on review of molecular genetics and basic genetic models
* Week 2 will focus on population genetics
* Week 3 will focus on genome-wide association studies

## Requirements
* Participants are expected to have completed the Shell and R learning modules prior to the course.
* No formal background in genetics is assumed. Basic concepts in molecular genetics will be introduced during the class.
* Participants should be familiar with key concepts in statistical inference, including:
  -  Elementary probability and statistical methods
  -  Distributions of basic random variables (e.g., binomial, normal)
  -  Likelihood-based methods, including estimation and hypothesis testing
  -  Basic regression techniques (e.g., linear and logistic regression)
* Participants are encouraged to ask questions and collaborate with others to enhance the learning experience.
* A computer and internet connection are required to participate in all online activities.
* Generative AI tools (e.g., ChatGPT) must not be used to generate code for assignments. However, they may be used as supportive tools to seek clarification or find answers to questions.
* Participants are expected to have completed the setup instructions provided in the onboarding repository.
* We encourage participants to keep their cameras on during sessions, turning them off only when necessary. This helps foster a more engaging and interactive learning environment and provides real-time feedback to the instructional team.

## Resources
Feel free to use the following as resources:

### Textbook
- The Fundamentals of Modern Statistical Genetics (Nan Laird & Christoph Lange).

### Videos
- Introductory Genomics Videos: [BigBio YouTube Channel – Genomics Playlists](https://www.youtube.com/c/BigBiovideos/playlists?app=desktop)


- Other useful resources beyond the scope of this course:
  - Biomedical Data Resource Guide: [StatsUpAI – Curated Biomedical Datasets](https://statsupai.org/datasets.html)


## Folder Structure

```markdown
.
├── .github
├── .gitignore
├── 01_materials
├── 02_activities
├── 03_instructional_team
├── 04_this_cohort
├── 05_src
├── LICENSE
└── README.md
```

* **.github**: Contains issue templates, pull request templates and workflows for the repository.
* **materials**: Module slides.
* **activities**: Contains self-assessments, graded assignments, and rubrics for evaluating assignments.
* **instructional_team**: Resources for the instructional team.
* **this_cohort**: Additional materials and resources for this cohort.
* **src**: Source code, databases, logs, and required dependencies (requirements.txt) needed during the module.
* **.gitignore**: Files to exclude from this folder, specified by the Technical Facilitator
* **LICENSE**: The license for this repository.
* **README**: This file.

