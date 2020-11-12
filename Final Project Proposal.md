# DATA 512 A Au 20: Human-Centered Data Science
# A4: Final Project Proposal
*Florencia Marcaccio*  
*Nov 12th, 2020*

## Table of Contents
1. [Motivation and problem statement](#motivation)
2. [Research questions and/or hypotheses](#research_questions)
3. [Data](#data)
4. [Metodology](#metodology)
5. [Background/Related Work](#background)
6. [Unknowns and dependencies](#unknowns)



## <a name="motivation"></a> Motivation and problem statement

The main goal of this project is to explore the relationship between gender and sports in the US.  I would like to understand if men have any advantages over women when it comes to institutional support. To narrow down the scope of this research, I will be focusing on collegiate sports, expecting that what I found here could be a fair representation of what is also happening on the professional level.  

Sports are a considerable aspect of college life, which influences many students' decisions on whether or not to attend a specific institution. Thus, I think it would be interesting to see if men and women teams are treated equally and fairly among US universities.  
  
After completing the project, I hope that I will learn whether women are given the same opportunities as men when it comes to collegiate sports. I will possibly obtain critical insights that can be also be associated with professional sports, to be explored in a later analysis.


## <a name="research_questions"></a> Research questions and/or hypotheses

I have two main hypothesis that I will be analyzing in this project:  

1. **H1: When women's teams receive low amounts of financial aid it results in poor participation in sports.**   

    1.1 Which states have the highest ratio of athetic student aid for women's team / athetic student aid for men's team?  
    1.2 Is there a relationship between student aid and the percentage of women participating in women's teams?  
    1.3 Does the amount of student aid affect recruiting expenses? And what about the expenses per participant and per team?   
    1.4 Do institutes that assign a higher amount of aid to women's teams have higher revenue for their women's teams?  
    1.5 Does being an institution with football affect the ratio of of financial aid given to women's teams?    

2. **H2: Working under the assumption that women's teams are not given the same importance, I would say that they are not given the same resources in terms of coaching staff.**  

    2.1 How many head coaches for women's and men's teams? How many assistant coaches for women's and men's teams?  
    2.2 What percentage of head/assistant coaches in men's teams are women, and what percentage of head/assistant coaches in women's teams are men?  
    2.3 Is there a difference in salary between coaches in women's teams vs coaches in men's teams?
  

## <a name="data"></a> Data

 
The dataset I'll use for this project contains 2074 US educational institutions with athletic programs that received federal student financial aid for the 2018-19 academic year. It has data on students' athletic participation, and staffing, revenues, and expenses by men's and women's teams.  
  
The dataset can be found in the [Download Data](https://ope.ed.gov/athletics/#/datafile/list) page of the [Equity in Athletics Data Analysis](https://ope.ed.gov/athletics/) website. The chosen data can be found under the year 2019, with the title "All data combined for academic year 2018-19". This will download a zip file with four files, of which I will use "EADA_2019.xlsx" and "EADA_2019.doc" (data and description, respectively). While there is no specified license, the dataset belongs under the [Equity in Athletics Disclosure Act](https://www2.ed.gov/finaid/prof/resources/athletics/eada.html) and was released to the public by the US Department of Education.  

This dataset is suitable for addressing the project goal as I can link the amount of resources and financial aid that women's and men's teams receive with how much university support they have. This will potentially disclose any unfair or biased treatment.  

One possible ethics issue that I see from using this dataset is that future students might be discouraged from even trying to pursue a career in sports if the analysis outcome is very pessimistic. However, if an unfair treatment is found, I think showcasing the findings is the key to start having the conversation about how to revert the situation.


## <a name="metodology"></a> Methodology

To clean and pre-process the data, I will be using Pandas and Numpy on the dataset. To answer each hypothesis's questions, I will be using a mixture of Pandas tables, statistical analysis, and data visualizations with Matplotlib and Seaborn.

For the first hypothesis, I will be using a bar chart for question 1.1 and scatterplots and a correlation heatmap for questions 1.2-1.4. I think visual explorations should provide enough evidence to answer these questions. I'm especially interested to see the correlation between the total financial aid for women's team and the ratio of financial aid that women's teams received against the other descriptive variables (expenses, revenue, participation) should present us with some evidence about the importance of athletic financial aid. For the last question, I will be performing statistical analysis to understand the effect of having football as one of the institution's sports. This last question could be an important one, as I believe that institutions that play football probably tend to give more attention and resources to that sport.   

For the second hypothesis, I will be using a mixture of methods. I will use a table for the first question, a bar chart for the second question, and a hypothesis test for the third one to see if there is any evidence to reject the null hypothesis of no difference in salary between coaches of women's and men's teams. Visualizations will also support this last question. The variety of exploration methods for this hypothesis should help us reach a definite conclusion. 


## <a name="background"></a> Background/Related Work

Girls' and women's participation in US sports is an issue that was brought to attention many years ago ([Do You Know the Factors Influencing Girls’ Participation in Sports?](https://www.womenssportsfoundation.org/do-you-know-the-factors-influencing-girls-participation-in-sports/)). While it has improved -a lot thanks to the sucess and notoriety of women in sports like soccer, gymnastics and basketball-, there are still many aspects that are far behind men's sports.

Most notably, the Women's Sports Foundation released its new national research report, ["Chasing Equity: The Triumphs, Challenges and Opportunities in Sports for Girls and Women,"](https://www.womenssportsfoundation.org/articles_and_report/chasing-equity-the-triumphs-challenges-and-opportunities-in-sports-for-girls-and-women/) which I think perfectly explains the current state of girls' and women's sports. The report covers many topics: participation opportunities, limitations, the role of Title IX, pay equity and equal treatment issues of women working in sports, and the media coverage of women's sports.

In addition, because of the quality of the data collected by the Equity in Athletics survey, there are several papers and articles that reference this dataset in their analysis of participation equality in sports ([Examination of Gender Equity and Female Participation in Sport., Joshua A. Senne (2016)](https://thesportjournal.org/article/examination-of-gender-equity-and-female-participation-in-sport/) and  [A Comparison Study of the Perceptions of Athletic Administrators towards Gender Equity in the CCCU and NCCCU Schools. Martha L. Marra (2016)](https://thesportjournal.org/article/a-comparison-study-of-the-perceptions-of-athletic-administrators-towards-gender-equity-in-the-cccu-and-ncccu-schools/), among others), usually focusing on one particular division classification.


## <a name="unknowns"></a> Unknowns and dependencies

There are no significant factors that I can foresee that would impact my ability to complete the project by the end of the quarter. The dataset is available in a friendly format, and, after a first exploration, data quality seems okay.  

The dataset also covers coed teams, but the data is more sparse for this category, so I will not include it in the analysis.  

As I plan on working only with the NCAA institutions, the 2018-19 dataset might not be enough for the project. If this is the case, I will include data from previous years, found on the same [website](https://ope.ed.gov/athletics/#/datafile/list) as the chosen dataset.
