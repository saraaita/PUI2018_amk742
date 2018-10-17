# Assignment 2 Review:

## 1. Hypothesis evaluation:

Having read the Idea for analysis, it is clear to me that the author wants to prove that distribution of lengths of journeys for men and women are different, to be specific, that for men on average it is significantly higher than for women. 
In general the stated hypothesis is understandable to the reader - I get a sense of what the author means. However, it lacks certain specifications that would make the hypothesis testable, despite giving the significance level. First of all, hypothesis lacks the word "on average" - without it, saying "time" does not really tell what we are going to measure, at all. Stating it directly specifies that we want to take a look at the durations from a holistic perspective, comparing the known statistics for two samples which is the mean. Secondly, it is not specified what data is given and what data will be studied under the test - whether we compare two samples, populations, and specifically, it lacks statement on which samples we take into account (the dates). The formula, given the aforementioned changes, should be restated to say mean instead of T. 

Given all the above, I would suggest the following changes to Null hypothesis:

Average duration of male trip in 01/2015 is lower or equal to average duration of female trip in the same time period, significance level:0.05.

Please note that despite the fact that all citibike data is provided, I assume we only compare two samples without population knowledge. This is assumption I decide to follow, however given we actually can calculate the population data, it could be restated accordingly.


## 2. Data 

The data for two genders and durations for a specific time period has been identified. I would suggest in addition to separate the two samples into two df objects (for male and female separately) and normalizing, since we are looking at the mean. At a first glance the distribution for both genders resembles Gaussian. 


## 3. Test

Under the assumption that we are looking at two samples (male and female) and do not look at population at all,  I would suggest using unpaired T test at the specified significance level. Z test could also be a solution, however we are looking specifically at the means, so according to the lecture slides, T test is more appropriate. 

