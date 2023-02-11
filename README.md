# Data Science Job Salaries 

<img src='what-is-data-science-1.webp' width=4500>


## What is data science?
**Data science** combines math and statistics, specialized programming, advanced analytics, artificial intelligence (AI), and machine learning with specific subject matter expertise to uncover actionable insights hidden in an organization’s data. These insights can be used to guide decision making and strategic planning. Due to importance of data science role, Nowadays, and the major changes the data scientist can do, we decide to analyze the salary of data science job titles and apply some Machine Learning models to help anticipate the future salary of data scientist.
 
[Data Science Definition source](https://www.ibm.com/topics/data-science)

## **Data Sience Job Titles are as follows:**

- 3D Computer Vision Researcher
- AI Scientist
- Analytics Engineer
- Applied Data Scientist
- Applied Machine Learning Scientist
- BI Data Analyst
- Big Data Architect
- Big Data Engineer
- Business Data Analyst
- Cloud Data Engineer
- Computer Vision Engineer
- Computer Vision Software Engineer
- Data Analyst
- Data Analytics Engineer
- Data Analytics Lead
- Data Analytics Manager
- Data Architect
- Data Engineer
- Data Engineering Manager
- Data Science Consultant
- Data Science Engineer
- Data Science Manager
- Data Scientist
- Data Specialist
- Director of Data Engineering
- Director of Data Science
- ETL Developer
- Finance Data Analyst
- Financial Data Analyst
- Head of Data
- Head of Data Science
- Head of Machine Learning
- Lead Data Analyst
- Lead Data Engineer
- Lead Data Scientist
- Lead Machine Learning Engineer
- ML Engineer
- Machine Learning Developer
- Machine Learning Engineer
- Machine Learning Infrastructure Engineer
- Machine Learning Manager
- Machine Learning Scientist
- Marketing Data Analyst
- NLP Engineer
- Principal Data Analyst
- Principal Data Engineer
- rincipal Data Scientist
- Product Data Analyst
- Research Scientist
- Staff Data Scientist


## **Team members**
| Team members   | Role |
| ----------- | ----------- |
| Rahaf | Dataset Providing, Clean and preprocess for dataset, EDA, Ploting 3 charts, write README markdown file, (LEADER) |
| Munirah | Apply Machine Learning, Ploting charts, write Read me file.|
| Moaath | Ploting chart, Apply Machine Learning.|


## **Dataset Overview**
The dataset is available through the :[Data Science Job Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)


## **Dataset Description**
| Column   | Description |
| ----------- | ----------- |
| work_year | The year the salary was paid. |
| experience_level | The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director |
| employment_type | The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance|
| job_title | The role worked in during the year. |
| salary | The total gross salary amount paid. |
| salary_currency | The currency of the salary paid as an ISO 4217 currency code. |
| salary_in_usd | The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).|
| employee_residence | Employee's primary country of residence in during the work year as an ISO 3166 country code. |
| remote_ratio| The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)|
| company_location | The country of the employer's main office or contracting branch as an ISO 3166 country code. |
| company_size | The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)|



## **Final Eight Insights**

|    | Insight |
| ----------- | ----------- |
| 1|  Most job titles for data science range from 6,000 to 200,000 and may exceed that|
| 2|  The avg salary of DS in the US is the highest regardless of the company size|
| 3|  In some country the size of the company dosen't determine the salary.|
| 4|  Russia, the United States and New Zealand are the highest paying countries for data science roles according to this dataset, paying mean annual salaries of $157,500, $144,055 and $125,000 respectively. |
| 5|  The US, The UK and Canada are the top three countries offering highest number of Data Science job.|
| 6|  Vietnam, the Iran and Kenya are the Lowest  paying countries for data science roles according to this dataset.|
| 7|  2020 have a low employment ratio due to covid-19 pandamic |
| 8|  Data analytics lead job have the highest salary avrage |


### **Models Results**
In our project we created a 4 models: Linear Regression , Decision Tree, Random Forest and Logistic Regression. The result of project are shown below:
| Model   | Accuracy |
| ----------- | ----------- |
| Linear Regression | r^2 = 0.33  |
| Decision Tree | 0.82 
| Random Forest | 0.82
| Logistic Regression | 0.84
