---
layout: post
title: "Alcohol Use Project (Part #2)"
subtitle: "Alcohol use and mental health in veterans with disabilities insights"
background: '/img/background_for_posts.jpg'
---

## Table of contents 
1- Part #1 recap <br>
2- Data source & Weighting <br>
3- Study sample & variables <br>
4- Statistical Analyses <br>



## Part #1 recap 
In part #1, we discussed the state of knowledge of the impact of alcohol use on mental health. We also reviewd studies about alcohol use in veterans with disabilities. Our research question is to assess whether there is an association between alcohol use and mental health outcomes in veterans with disabilities. In this post, we try to learn more about the data we want to use in this project. 



## Data source & Weighting
The data we will be using is the 2020 Behavioral Risk Factor Surveillance System (BRFSS) which is a cross-sectional annual telephone survey in the United States. It is conducted by the Centers for Disease Control and Prevention (CDC) and health departments to collect behavioral health risk data from adult U.S. residents on their health-related risk behaviors, chronic health conditions, and preventive service use. BRFSS questionnaire includes (1) core questions (which are asked by all states), (2) optional modules (which are based on specific topics), and (3) state-added questions [(CDC, 2013).](https://www.cdc.gov/brfss/data_documentation/pdf/UserguideJune2013.pdf) 

In order to make generalizations from the sample to the population and to reduce bias, we need to weight the data. The BRFSS uses an iterative proportional fitting (or raking) which can adjust for demographic differences that can be found between sample and population. The first method they used is "design weights" which are calculated from geographic stratum weight. The second method is raking which can help if groups are underrepresented in the sample and require to be accurately
represented. [More information about the BRFSS weighting process can be found here.](https://www.cdc.gov/brfss/annual_data/annual_2020.html) 




## Study sample & variables 

In order to define our sample which is veterans with disabilities, we focus on: (1) disability status, (2) veteran status. 

<em>Disability Status</em>

To determine disability status, participants were asked the following questions: “Some people who are deaf or have serious difficulty hearing may or may not use equipment to communicate by phone. Are you deaf or do you have serious difficulty hearing?” (hearing); “Are you blind or do you have serious difficulty seeing, even when wearing glasses?” (vision); “Because of a physical, mental, or emotional condition, do you have serious difficulty concentrating, remembering, or making decisions?” (cognition); “Do you have serious difficulty walking or climbing stairs?” (mobility); “Do you have difficulty dressing or bathing?” (self-care); “Because of a physical, mental, or emotional condition, do you have difficulty doing errands alone such as visiting a doctor’s office or shopping?” (Independent living). Respondents were defined as having a disability if they answered “yes” to any of the disability questions. [More information on creating the disability status can be found here.](https://www.cdc.gov/brfss/data_documentation/pdf/BRFSS_Data_Users_Guide_on_Disability_Questions_2018-508.pdf) Additional information on disability questions and types can be found [here.](https://www.cdc.gov/ncbddd/disabilityandhealth/dhds/data-guide/status-and-types.html) 

<em>Veteran Status</em>

To determine disability status, participants were asked, “Have you ever served on active duty in the United States Armed Forces, either in the regular military or in a National Guard or military reserve unit? Active duty does not include training for the Reserves or National Guard, but DOES include activation, for example, for the Persian Gulf War.” [Respondents were considered veterans if they responded “yes” to this question.](https://www.cdc.gov/ncbddd/disabilityandhealth/dhds/data-guide/demographics.html)


**Outcome variable**

For our outcome variable, we will be using the Health-related Quality of Life-4(HRQOL), which has been used in previous studies [to assess the prevalence of mental distress.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6110180/)

<em>Health-related Quality of Life-4 (HRQOL)</em>

The CDC defines HRQOL as “an individual’s or group’s perceived physical and mental health over time” [(CDC, 2000).](https://www.cdc.gov/hrqol/pdfs/mhd.pdf) To analyze the health-related quality of life (HRQOL) among veterans with disability, we will analyze the veterans responses to the HRQOL question that is included in BRFSS “Healthy Days” module. 
The question is as follows:

• “Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good?”

To obtain an estimate of a person’s overall unhealthy days, we will dichotomize the question to have individuals that reported 14 or more days of poor mental/physical health and individuals who had less unhealthy days [(Edwards 2016).](https://pubmed.ncbi.nlm.nih.gov/27759499/)

**Explanatory variable** 

[<em>Binge drinking</em>](https://www.cdc.gov/brfss/annual_data/2020/pdf/2020-calculated-variables-version4-508.pdf)

 During the past 30 days, five or more drinks for males and four or more drinks for females on one occasion.


[**Demographic Variables**](https://www.cdc.gov/ncbddd/disabilityandhealth/dhds/data-guide/demographics.html)


<em>Employment status</em>

 “Are you currently—employed for wages, self-employed, out of work for 1 year or more, out of work for less than 1 year, a homemaker, a student, retired or unable to work?” We recorded the variable to have three levels: “Employed,”Not Employed,” and “Retired” 

<em>Marital status</em>

 “Are you—married, divorced, widowed, separated, never married or a member of an unmarried couple?” We reduced the variable to have “Married or living with a partner,” “Separated/divorced/ widowed,” and “Never married” 

<em>Education level</em>

 “What is the highest grade or year of school you completed?” The levels included are “Did not graduate High school,” “Graduated high school,” “Attended college or Tech school,” and “Graduated from college or Tech” 

<em>Income level</em>

 “Is your annual household income from all sources—” with the following categories: <$15,000, $15,000 to <$25,000, $25,000 to <$35,000, $35,000 to <$50,000, and $50,000+

<em>Race/ethnicity</em>

 “White, Non-Hispanic,” “Black, Non-Hispanic,” “Asian, American Indian/ Alaskan Native, other race Non-Hispanic,” and “Hispanic”

<em>Sex</em> 

Male or Female

<em>Age</em>

Six categories, 18 to 24, 25 to 34, 35 to 44, 45 to 54, 55 to 64, and 65 or older







## Statistical Analyses

We will use quantitative methods to assess the relationship between veterans with disabilities mental health outcomes (mentally unhealthy days) and binge drinking. First, we will conduct descriptive analysis to examine the demographic characteristics, mental health outcomes, and binge drinking among veterans with disabilities. Then, multivariate logistic regression analysis will be conducted to assess the relationship between binge drinking and mentally unhealthy days.