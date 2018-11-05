# Visualizations

In this notebook, I am going to explore a dataset on the job outcomes of students who graduated from college between 2010 and 2012. Th original data n the job outcomes was released by American Community Survey and cleaned by FiveThirtyEight https://github.com/fivethirtyeight/data/tree/master/college-majors

I will try to answer the following questions What is the gender distribution ofn the top ten majors by the total number of graduates? What are the top ten highest-paying majors and which gender is the majority of these majors? What are the ten lowest paying majors and which gender is the majority? What is the gender distribution by major category What is the unemployment rate per major category? and what are the top ten majors with the highest percentage of the unemployment rate?

Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Here are some of the columns in the dataset:

Rank - Rank by median earnings (the dataset is ordered by this column).
Major_code - Major code.
Major - Major description.
Major_category - Category of major.
Total - Total number of people with major.
Sample_size - Sample size (unweighted) of full-time.
Men - Male graduates.
Women - Female graduates.
ShareWomen - Women as share of total.
Employed - Number employed.
Median - Median salary of full-time, year-round workers.
Low_wage_jobs - Number in low-wage service jobs.
Full_time - Number employed 35 hours or more.
Part_time - Number employed less than 35 hours.
