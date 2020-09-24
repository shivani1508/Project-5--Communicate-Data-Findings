# Project-5--Communicate-Data-Findings
### Project Overview:
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

### Why this project?
Data visualization is an important skill that is used in many parts of the data analysis process. 

Exploratory data visualization generally occurs during and after the data wrangling process and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. 

Explanatory data visualization techniques are used after generating your findings and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to be a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

### Part 1: Conduct an exploratory data analysis on a dataset of your choosing.

<b> Step 1: Choose your Dataset

Dataset chosen: Ford GoBike System Data

<b> Step 2: Explore Your Data

It’s time to get to the interesting bits. Explore your data and document your findings in a report. The report should briefly introduce the dataset, then systematically walk through the points of exploration that you conducted.

#### In this project, I have made the comparison of first 3 months (Winter Months) January, February and March of the year 2019 and year 2020. 

The following dataset( containinig data of January, February and March) are used:

- combined dataset df_bike_clean of the year 2019- 2020
- Dataset df_bike_clean_2019 for exploring trends of year 2019
- Dataset df_bike_clean_2020 for exploring trends of year 2020

Performed Preliminary Data Wrangling on the dataset and cleaned data (replacing Null values, dropping Duplicates and changing Datatypes of certain columns). Also, new columns such as start_time_year, start_time_month_no, start_time_month, start_time_weekday, duration_min, start_time_hour, end_time_hour are added for analysis.

Following Explorations are made using appropriate plot types, and conclusions are drawn.

- Univariate Exploration
- Bivariate Exploration
- Multivariate Exploration

### Part 2: Take your main findings from your exploration and convey them to others through an explanatory analysis.

Summarized the main findings and reflected on the steps taken in my data exploration. 

- Ford GoBike System usage by Days in Month - 2019 vs. 2020: shows that there was an increase in the usage in the year 2020.
- Hourly usage of the Ford Go Bike System 2019 vs 2020: the usage pattern seems to be quiet similar in both the graphs, stating the reasons of the users to use the system were similar in 2019 and 2020.
- Ford GoBike System - Customers vs. Subscribers: shows the % of user types. The customer % in year 2019 was 12.7% and in the year 2020 it is 40.1%, which shows the marketing team was able to attract other user type successfully and the demand of the system increased, resulted in the higher number of trips.
- Ford GoBike System Trends by User Type- Customers and Subscribers vs. Year: Subcribers follow the same pattern. Maximum usage over weedays Mon-Fri and it decreases over weekend Sat-Sun.While customers in both the years have in-verse pattern. 2019, the customer usage increases over weekend Sat-Sun while in 2020, the usage is more on weekdays Mon-Fri and drecrease on weekends Sat-Sun.
- Ford GoBike System - Start Time vs. Day of Week by User Type - 2019: Subcribers tends to use FordGoBike System on weekdays Mon-Fri the most, during the time 8am-9am and 5pm-6pm. While Customers are using the system on weekends Sat-Sun, at 2 pm the most on Satudays and 12pm-2pm on Sunday which is relatively hotter hours in the winter months.
- Ford GoBike System - Start Time vs. Day of Week by User Type - 2020: Subcribers and Customers both tends to use FordGoBike System on weekdays Mon-Fri the most, during the same time of 8am-9am and 5pm-6pm, while considerably very less rides have been take on weekends.

