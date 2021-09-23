---
layout: post
title: Group Assignment for Applied Statistics
date: 2021-09-21
---

> Group Assignemnt

## Executive Summary

#### Dataset Limitations:

Although the sample size of this data set is 26765, it is important to take into account that it is not a random sample. Since it is sourced from the website askamanager.org, the respondents are already predisposed to fit some sort of group. For example, most respondents have a job already and more than half have received a college education or above. That being said, here are the key takeaways of our analysis on the askamanager salary survey.

#### Key Takeaways:

1.  Gender and Salary: Overall there is a statistically significant salary gap between men and woman in the dataset. This is confirmed through multiple methods such as plotting the data, running a T.Test, calculating a confidence interval, and than testing our results through bootstrapping. As we looked deeper, however, there are some key differences in the gender salary gap in different industries. To start, the largest gap is seen in the Law industry, which has on average a $40,000 difference in salary between men and woman. In comparison, in the Art and Design industry the gender gap switches, as woman have higher average salaries in the field by about $10,000.

2.  Changing Industry and Salary: During our data analysis we were curious to see whether changing industries lead to higher annual salaries. We created a graph to depict this and we found that those who didn't switch industry had higher salaries. We then ran a T.test that showed that this difference in average salary between those that remained in the same industry and those that switched was statically significant. In addition, when looking at industry, for both men and women Law is the industry with the highest salary levels. In addition, individuals working in law have the highest education levels. This brings us to our next point of the relationship between education and salary.

3.  Education and Salary: Education level was shown to be statistically significant in explaining variation in annual salaries in our linear regression models. Those with professional degrees (MD, JD, etc) on average earned higher salaries. The gender gap is also prevalent within the respondents who have higher education levels. The pay gap between genders is highest at the high school level and gradually lowers until the professional degree level. This shows that as education levels increase, the salary gap gets lower. There is however an exception with the gender pay gap spiking with PhDs.

4.  As one would expect, we found that as years of experience in the field increased, average annual salary also increased. This is because as people can more experience they can provide more value and garner a higher salary. This was shown in the regression models with the different levels in years of experience all being statistically significant.

5.  Salary and Race: When looking into the intersection of salary and race, we picked the three races with at least 500 respondents - White, African American or Black, and Asian or Asian American. When plotting the data in a boxplot format, we could easily see that the Asian race had on average higher salaries. However, boxplots for the White and African American or Black races were very similar and we decided to run a T.test. The T.test ended up calculating a P value of .3, thus we can conclude that there isn't a statistically significant difference between the means in salary of these two races.

\#Can mention EDA results are supported by t.tests (should be done - included above)

Explain stuff using t.tests and models

Regression & Results on Test data:

1.  Experiences in a specific filed explain more variance of salaries, rather than age or the years of professional experience in total.

2.  Data related jobs are averagely paid higher by $5046 than other jobs, scientists are paid higher by $8820.476 and data scientists are paid higher by approximately *$31300* in the survey. But doing a database related job gets even $12360 lower salary. Engineers on average earn $22182 more per year and managers earn $7987 more than average. Doing a research job has no significan positive effects on salary.

3.  Races do have influences on salaries *in the survey*. Asians (4.54% of the respondents) earn the most and white people (84.68%) earn the lowest on average. That may be caused by the bias of sampling.

4.  Population of the state has positive effects on average salary. People in a state with 1 million more people averagely earn $383 more.

5.  The performance of final model RMSE on train data: 28801. RMSE on test data: 28398. R Squared on train data 42.30%. R Squared on test data 44.23%. That indicates there is no overfitting problem but still space to improve.





