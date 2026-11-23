# Overview

The project was created to understand the Job Market, particularly focusing around Data Related Roles more effectively. It focuses on the top-paying and in-demand skills to help find optimal job opportunities for data analysts.

# Key Questions Answered

1. What are the most demanded skills for the top 3 most popular data roles?

2. How are in-demand skills trending for Data Analysts?

3. How well do jobs and skills pay for Data Analysts?

4. What is the most optimal skill to learn for Data Analysts?

# Tools Used

- **Python:** Usage of the language and also critical libraries like *Pandas, Matplotlib, and Seaborn* for data manipulation, cleaning and visualization aiding final analysis

- **Jupyter Notebooks:** Tool used to run python scripts and obtain desired output for analysis

- **Visual Code Studio:** Platform for executing the python scripts on Jupyter Notebook

- ** Git & GitHub:** For version control and sharing Python Code and Analysis 

# The Analysis
### 1. What are the most demanded skills for the top 3 most popular data roles?

Skills Demand Analysis

The analysis focuses on the three most popular roles: Data Analyst, Data Scientist, and Data Engineer, with the geographic scope restricted to the United States.

The top five skills for each role were identified by counting skill mentions after exploding the 'job_skills' column. Skill demand was calculated as the percentage of total job postings for each role that mentioned a particular skill.

#### Key Findings:

![alt text](<Project 1 (Luke Barousse)/Final Project/images/Skills_Demand_Picture.png>)


SQL and Python are among the most in-demand skills across all three roles, particularly for Data Scientists and Data Engineers.

Data Analyst roles show stronger demand for SQL, Excel, and Tableau, reflecting their emphasis on data analysis, reporting, and business intelligence.


The findings, for the top 5 skills for each of the three most popular roles were shown as below.

It was observed that sql and python were the most prominent and common skills which were part of Data Scientist and Engineer roles since they are more inclined towards the technicalities of Data

But Data Analyst Roles required sql, excel and tableau more often since it revolves more around the business aspect and hence requires less technical skills around the data domain.

The detailed analysis using Python can be found in the link 

[2_Skills_Count.ipynb](Project%201%20(Luke%20Barousse)/Final%20Project/2_Skills_Count.ipynb)


### 2. How are in-demand skills trending for Data Analysts?

The geography was again limited to the United States, where the top 5 most in-demand skills based on the number of times they were mentioned in a job posting were
 - sql
 - excel
 - tableau
 - python
 - power bi

The following things were observed:

![alt text](image.png)

- sql remained the most dominant skill, through gradually dipping in terms of requirement towards the later months of 2023, still remained highly dominant and relevant
- excel was the second most required skill but showed unsteadyness in terms of its trend
- tableau and python were jointly popular with python requirement showing a dip before the last quarter and then surging in the last quarter 
    - both of them maintained a stable pattern in terms of requirement as a skill
- power bi was the least popular among the top 5, still maintained steady requirement

#### Takeaway

- sql, excel and python maintains their relevance despite some gradual dips in some of their trends but remain the most popular skills to have handy for Data Analyst roles
- The rest of the skills are also good to know even thoough they are not as highly demanded as SQL and excel
- All 5 skills show relatively stable trend standing in 2023, and will be handy for Data Analyst Roles

The steps followed for the conclusion are documented in the following link:

[3_Skills_Trend.ipynb](<Final Project/3_Skills_Trend.ipynb>)

### 3. How well do jobs and skills pay for Data Analysts?

![](<Project 1 (Luke Barousse)/Final Project/images/Salary Analysis.png>)

- Senior Data Scientists command the highest median salary at $155K, followed by Senior Data Engineers at $150K.

- Data Analysts have the lowest median salary at $90K, highlighting a significant pay gap compared to other data roles.

- Data Scientists and Data Engineers have relatively wider salary distributions, indicating greater variation in compensation.

- Senior roles generally offer higher median salaries than their non-senior counterparts, reflecting the premium associated with experience and specialization.

- Data Scientists show the highest salary outliers, with a few salaries exceeding $550K.

- Data Analysts and Senior Data Analysts have comparatively narrower salary distributions, suggesting more concentrated compensation ranges.

- Salary distributions are positively skewed across all roles, with several high-paying outliers extending beyond the upper whiskers.

#### When analysing the skills

![alt text](<Project 1 (Luke Barousse)/Final Project/images/pay vs skills.png>)

It is observed that:

- Skills involving cloud technologies have the highest salaries but when deep dived into, the jobs with such requirement are very rare as shown below

| Job Skill | Count | Median Yearly Salary |
|:---|---:|---:|
| dplyr | 2 | $196,250 |
| bitbucket | 3 | $189,000 |
| gitlab | 3 | $186,000 |
| solidity | 1 | $179,000 |
| hugging face | 1 | $175,000 |
| couchbase | 1 | $160,515 |
| ansible | 1 | $159,640 |
| mxnet | 2 | $149,000 |
| cassandra | 6 | $148,250 |
| vmware | 1 | $147,500 |

- On the contrary, the most requested skills have high requirements and decent salary brackets around $80K to $100K

| Job Skill | Count | Median Yearly Salary |
|:---|---:|---:|
| python | 1,431 | $97,500 |
| tableau | 1,364 | $92,875 |
| r | 893 | $92,500 |
| sql server | 286 | $92,500 |
| sql | 2,508 | $91,000 |
| sas | 926 | $90,000 |
| power bi | 838 | $90,000 |
| powerpoint | 462 | $85,000 |
| excel | 1,808 | $84,392 |
| word | 461 | $81,195 |

- Also, knowing more advanced technologies like python, r, sql, pays more than basic skills like powerpoint, excel and word

Although certain specialised skills command significantly higher salaries, the number of available opportunities is relatively limited. 

In contrast, developing widely sought-after skills with strong market demand may offer greater practical value and broader career opportunities.

The steps followed for the conclusion are documented in the following link:

[4_Salary_Analysis.ipynb](Project%201%20(Luke%20Barousse)/Final%20Project/4_Salary_Analysis.ipynb)


### 4. What is the most optimal skill to learn for Data Analysts?

![alt text](<Project 1 (Luke Barousse)/Final Project/images/Skill vs Salary.png>)

- Focus should be more on programming and analyst tools to get high paying and broader range of opportunities

- Technologies like **python, tableau and sql are the most common and decently paying skills** required for analytics

- Power BI, r and SAS technologies lie in the mid segment of requirement and salaries, they are relevant in terms of pay but are relatively lesser required than SQL

- Some technologies can secure very high pay like oracle, sql server, but have very rare job postings with the requirement of the same, hence limits opportunities

- Lastly, analyst tools like excel, word and powerpoint are the most basic skills for Data Analysts, which will open entry level salaries

Detailed steps can be found in the link below:

[5_Optimal Skills.ipynb](Project%201%20(Luke%20Barousse)/Final%20Project/5_Optimal%20Skills.ipynb)

# Core Insights

\- **SQL and Python are the most valuable foundational skills:** They consistently rank among the most demanded skills across Data Analyst, Data Scientist, and Data Engineer roles, making them highly transferable across the data domain.

\- **Data Analyst roles prioritise business intelligence and reporting:** Excel, Tableau, and Power BI complement SQL and Python, highlighting the importance of translating data into actionable business insights.

\- **Specialised technologies offer higher salaries but fewer opportunities:** Skills such as cloud technologies, GitLab, Couchbase, and Solidity command higher median salaries, but their limited demand makes them less reliable as primary career investments.

\- **The optimal strategy is to balance demand with earning potential:** Building proficiency in SQL, Python, and visualisation tools such as Tableau or Power BI offers a stronger combination of employability, career flexibility, and competitive compensation than focusing exclusively on niche, high-paying technologies.

# Conclusion

The exploration into the job market was informative, highlighting critical skills and their relevance, along with their trend with time.

The analysis can be useful to provide actionable guidance with respect to relevant skills and at the same time provide realistic expectation setting as to the pay and relevance of existing and required skillset.
