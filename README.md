# Data-Science-Salary-Analysis-India
- Analysed the salary pattern of data science related fields in **India**.
- **Scrapped** the data from the glassdoor.
- Performed **Data Cleaning and Data Featurization**.
- Perform **Data Analysis(EDA)** on the data to get the insides of the trends in Salary of data science related fields.

## Glassdoor data scrapping
 - Scraped around 800 job descriptions from glassdoor using python and selenium.Data is scrapped in may 2020.
 - With each job, we scrapped the following: **Job title,Salary Estimate,Job Description,Rating,Company,Location,Company Headquarters,Company Size,Company Founded Date,Type of Ownership,Industry,Sector,Revenue,Competitors**
- Refered a very good article for scrapping.
- Link of the article-->https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905
- Made changes in the code of the article and made it to our requirements.Also glassdoor changes the place to html tags frequently so that there data can not be scrapped easily.
- Tackled the problem of pop window pops when ever tries to scrap the data.

<img src="readme resources\glassdoor job alert.png" alt="create job alert popup window" width="400" height="250" />

## Data Cleaning and Data Featurization
After scraping the data,cleaned it up so that it was usable for Analysis. I made the following changes and created the following variables:-
- Removed the rows without salary.
- Create a new column avg_salary that consist of the average salary as the salary that was scrapped was in the form of rang(eg:-₹27K - ₹29K).
- Cleaned company name,founded,job description.
- Created simplified_job_title_column that have the simplified job title on the basis of certain conditions.It will made are analysis easy as there are many different job titles in the data.

## Data Analysis(EDA)
Below are few highlights of the Analysis.

<img src="readme resources\top_cities.png" alt="top_cities that have max jobs" width="400" height="250" />

<img src="readme resources\salary_by_role.png" alt="salary_by_role" width="400" height="250" />

<img src="readme resources\top_salary_by_ownership.png" alt="top_salary_by_ownership" width="400" height="250" />

## WordCloud Of Description
<img src="readme resources\WordCloud.png" alt="WordCloud" width="700" height="400" />

**Give a ⭐ if you like it or if this repository helped you in any way.**

**Thank You..**
