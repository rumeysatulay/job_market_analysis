# Job Market Analysis

## Overview

In this project, I examine job postings related to data. I evaluate jobs in various ways, with a focus on postings in the US due to their diversity. I assess job locations, whether they are remote or not, and salaries in different ways. Additionally, I analyze the top skills required for these jobs and the skills associated with high-paying positions. In summary, this project provides a comprehensive analysis of data-related jobs in the US.

## Dataset

The dataset used in this project is taken from `lukebarousse/data_jobs`. It contains various details about job postings, including:

- `job_title_short`
- `job_title`
- `job_location`
- `job_via`
- `job_schedule_type`
- `job_work_from_home`
- `search_location`
- `job_posted_date`
- `job_no_degree_mention`
- `job_health_insurance`
- `job_country`
- `salary_rate`
- `salary_year_avg`
- `salary_hour_avg`
- `company_name`
- `job_skills`
- `job_type_skills`

## Project Goals

- **Analyze Job Distribution by Location**: Determine the number of data-related jobs available in various locations across the US.

- **Identify Key Skills for Top Data Roles**: Find the most demanded skills for the top 3 most popular data roles.

- **Track Skill Trends Over Time**: Analyze how the demand for specific skills has evolved over time according to the posting dates.

- **Top 10 Most In-Demand Skills for Data Analysts**: Identify the top 10 skills most frequently required for data analyst positions.

- **Top 10 Highest-Paid Skills for Data Analysts**: Determine the top 10 skills associated with the highest salaries for data analysts.

- **Evaluate Optimal Skills for Data Analysts**: Assess which skills are most effective and advantageous for data analysts in the US.

## Process 

Python was the cornerstone of my analysis, enabling me to thoroughly examine the data and uncover crucial insights. I utilized several Python libraries to enhance this process: the Pandas library for data analysis, Matplotlib for visualizing the data, and Seaborn for creating more sophisticated visualizations.

## Outcomes

- This graph highlights the top 10 locations in the US with the most job postings, including a category for "Anywhere," which covers postings that are location-agnostic or remote. This information is valuable for job seekers as it shows where the highest number of job opportunities are available, helping them focus their job search on regions with more options.

![png-2](https://github.com/user-attachments/assets/59b81280-bae1-4ed1-abf5-f4e241f82b8c)

- This graph shows the top 10 companies with the most job postings. It provides valuable information for job seekers in the data field in the US, guiding them on which companies are currently hiring the most and where they might consider applying.

![png-3](https://github.com/user-attachments/assets/c2053447-4fdf-4480-aa6e-5baecd7d1f74)

- To determine the most demanded skills for the top three most popular data roles, I began by examining the list of job skills provided in each job posting. I first exploded the job skill columns to analyze each skill individually. Then, I grouped the data by job skill and job title. This process resulted in a table showing the count of each specific job skill for each job title, enabling a detailed assessment of skill demand for the top data roles.

![png-4](https://github.com/user-attachments/assets/e42b51df-856d-4a16-99a9-b06a77078247)

- Using this list, I identified the top three jobs with the highest skill count, which are Data Analyst, Data Engineer, and Data Scientist.
-
- In this graph, the skill request percentage for the top three popular job titles—Data Analyst, Data Engineer, and Data Scientist—is shown. We can see that SQL and Python are common skills across all three roles. Excel is the second most important skill for Data Analysts, but it is not as crucial for Data Engineers and Data Scientists. This chart is important for those who want to transition to one of these top three jobs or are seeking employment; these are the skills they need to have.
  

![png-5](https://github.com/user-attachments/assets/9cc8d639-17c5-49bc-875e-f14c1df4f97f)












