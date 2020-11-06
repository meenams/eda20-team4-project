# Next Steps

1. Everyone download data and brainstorm guiding questions

Code to download and combined the data sets:

NY <- read.csv("glassdoor_data/Data_Job_NY.csv")

SF <- read.csv("glassdoor_data/Data_Job_SF.csv")

TX <- read.csv("glassdoor_data/Data_Job_TX.csv")

WA <- read.csv("glassdoor_data/Data_Job_WA.csv")

ds_jobs <- rbind(NY, SF, TX, WA)

# Brainstorm of questions

## 1. Motivating Question

As a data scientist looking for a job, where and what are my best options?

Best all-around options could include:

* Most job openings in the area
* Best salary compared to cost of living
  * How do we handle salary ranges?
* Best rated companies/industries in the area
* Which job titles have the best salary and/or most job openings?

### 1 a) Follow up questions

What are some key skills and experience needed?
* Text analysis of the job descriptions

When is the best time to look for jobs?
* Data is only for a couple months so maybe day of the week? 
* Or this could be an analysis of what is going on with data science jobs during the start of the covid-19 pandemic

# Questions to the Group

* How do we handle the regions? by city, by state, metro area? We would need to find a way to group by metro area.

* Can we scale min and max salaries for cost of living in each area?

* Data was scraped right after the pandemic started so how does this affect our analysis?
