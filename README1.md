# dsi_projects

Project 1

Making SAT the preferred choice - for State Education Administrators

Background for this study:
Participation in the college admission tests has increased, due to various factors, such as,
    Mandatory requirements for admission to institutes of higher learning
    Fee waivers offered by states 
    SAT is working to expand its market share in recent years by revising the test and entering into deals with numerous states and school systems to give students the exam. 
Increase in number of students has impacted some state average scores
This study is also an opportunity to assess the performance of the 2017 and 2018 cohorts in the ACT and SAT tests

Reference:
https://en.wikipedia.org/wiki/List_of_standardized_tests_in_the_United_States#Admissions_tests
https://www.usnews.com/education/best-colleges/articles/2018-01-23/how-to-take-the-sat-act-for-free
https://www.edweek.org/ew/articles/2017/09/07/us-students-scores-inch-up-on-latest.html


SAT is increasingly the ‘preferred’ test with 100% participation in 5 states currently. However, the SAT board would like to expand and reach out to other states for more participants to adopt SAT as their preferred choice.

A part of this study:

State-wise scores for individual components of ACT and SAT (years 2017 and 2018) were collected and studied
Means of analysis used including,
    Calculation of mean and std deviation
    Calculation of quantiles (25, 50 and 75 quantiles)
    Study of skewness and distributions of scores
    Hypothesis testing
    
Limitations of the study:
Available data is for only 2 years, hence it is hard to predict trends. 
Timing is critical as many states are relooking at the ACT and SAT and policy decisions are being made on whether these should be mandatory or optional. Also, the cost of these decisions is an important factor for the administration. 
Colleges are questioning the holistic nature of tests and some are considering scrapping them totally. As of January 2018, over 1,000 colleges and universities have stopped requiring SAT or ACT scores for undergraduate applicants.

Strategies to convince state officials that SAT should be their choice: 
Share about past record of 2 years to show how the cohorts have done well 
Ave SAT scores have grown along with SAT participation rates
Provide support to administrative faculty in organising for the test and students taking up the test - for furtehr discussion
Conduct test on weekday to ensure high participation - for further discussion
Any other incentives for administrators - for further discussion
Feedback from colleges / institutes of higher learning on how SAT can be made more holistic


Data Dictionary:

Feature 	Type 	Dataset 	Description
state 	object 	ACT /SAT 	Name of State
act20**_participation 	float 	ACT 	average %
act20**_eng 	float 	ACT 	average score
act20**_math 	float 	ACT 	average score
act20**_reading 	float 	ACT 	average score
act20**_science 	float 	ACT 	average score
act20**_composite 	float 	ACT 	average score
sat20**_participation 	float 	SAT 	average %
sat20**_evi_based_read_write 	float 	SAT 	average score
sat20**_math 	float 	SAT 	average score
sat20**_total 	float 	SAT 	average score
