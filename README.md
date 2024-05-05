# Uber-Case-Study_Python
![pic](https://github.com/HafshaWahab/Uber-Case-Study_Python/assets/152807534/c8617b9c-5cff-4677-8bed-16a0e67f1920)

## Background
DailyUber provides the 2016 data for 2 weeks. Using this data set, the cab's demand and supply analysis gap has been tried to find out. The main objective of this project is to analyze the data on Uber Request data. Through data analysis, some important insights could be generated which could help improve the smooth experience of customers and drivers.

## About dataset
[Data Source](https://www.kaggle.com/datasets/nanasahebshinde/uber-case-study/data)

**App Openings (Eyeballs) =** Customers who launch the app looking for riders. It is a good measure of demand

**Zeroes =** Customers who open the app and see no cars in the area.

**Request =** Customers who make requests for a car.

**Completed Trip =** The point from when a customer is picked

## Case Study Analysis

1.	Which date had the most completed trips during the two weeks?
2.	What was the highest number of completed trips within 24 hours?
3.	Which hour of the day had the most requests during the two weeks?
4.	What percentages of all zeroes during the two weeks occurred on weekends (Friday at 5 pm to Sunday at 3 am)? (Tip: The local time value is the start of the hour (e.g. 15 is the hour from 3:00 pm - 4:00 pm))
5.	What is the weighted average ratio of completed trips per driver during the two weeks? (Tip: "Weighted average" means your answer should account for the total trip volume in each hour to determine the most accurate number in the whole period.)
6.	In drafting a driver schedule in terms of 8-hour shifts, when are the busiest 8 consecutive hours over the two-week period in terms of unique requests? A new shift starts every 8 hours. Assume that a driver will work the same shift each day.
7.	True or False: Does driver supply always increase when demand increases during the two-week period? (Tip: Visualise the data to confirm your answer if needed.)
8.	In which 72-hour period is the ratio of Zeroes to Eyeballs the highest?
9.	If you could add 5 drivers to any single hour of every day during the two-week period, which hour should you add them to? (Hint: Consider both rider eyeballs and driver supply when choosing)
10.	True or False: Are there exactly two weeks of data in this analysis?
11.	Looking at the data from all two weeks, which time might make the most sense to consider a true "end day" instead of midnight? (i.e when are supply and demand at both their natural minimums) (Tip: Visualise the data to confirm your answer if needed.)

## Methodology
1) **Data Understanding** - performed EDA to understand the general information about the dataset.
2) **Data Processing** - converted data type of the 'Date' field, removed whitespaces from field names and renamed some of the field names.
3) **Data Visualization** - performed analysis and solved the given questions, and by using Matplotlib library visualised the dataset.

## Findings
1. 2012-09-22 with 248 trips has the maximum no. of trips in the 2-week period.
2. The max. no. of trips completed in a 24-hour period was 248.0.
3. The maximum requests are placed at 23 hr.
4. The percentage of Zeroes is 44.9% when the customers open the app but could not find the app.
5. The weighted average ratio of completed trips per driver during the 2 weeks period is 0.63
6. The busiest 8-hour period starts at 22:00 and ends at 06:00.
7. False
The demand for driver supply does not increase with demand.
8. The 72-hour period with the highest Zeroes to Eyeballs ratio is on 2012-09-23 with a ratio of 0.35
9. Add 5 drivers to the hour at 2 AM to maximize efficiency.
10. True, the data is of 2 weeks time.
11. We can consider 4 AM as the end day where demand and supply both are at their minimum value of: 0.79

