# Sales-Data Analysis
# Introduction
This project was done using Excel during my Excel class with Dahel Techies. 
# Data Collection
This data was given to me to work on in my data analysis class with Dahel Techies
The data had 10 columns and 17,422 rows.
# Data preparation
* There was no duplicate or missing value
* I created a new column for year and weekday from the order date that was provided
* I merged the first name and last name column together as the customer name and put it in lowercase.
* I derived a new column for customer age from the birthdate and order date
* I used the IF function to put the age in categories. =IF([@[Customer''s age]]<=19, "Teenager", IF([@[Customer''s age]]<=34, "Young Adult", IF([@[Customer''s age]]<=49, "Adult", IF([@[Customer''s age]]<=64, "Seniors", IF([@[Customer''s age]]>=65, "Elderly", FALSE)))))
# Key Questions
1. What is the minimum revenue generated? 
2. What is the maximum revenue generated?
3. What is the average revenue?
4. What is the customer value based on spend?
5. Determine the sum of revenue based on country and gender.
6. Revenue spent based on age.
# Data Visualization
![image](https://github.com/Imoniyi/Sales-Data/assets/151396523/ec1441fb-7cc2-47b5-afe7-5ca42bf5cd64)


![image](https://github.com/Imoniyi/Sales-Data/assets/151396523/0b904f21-be65-4595-ab4c-8855343ab054)

![image](https://github.com/Imoniyi/Sales-Data/assets/151396523/0ed4ce93-26e2-48ee-b167-3e946b9535da)

# Interpretation and findings 
* The minimum revenue generated was £3 and the maximum revenue generated was £5,398.
* The average revenue generated was £1249
*Out of the 10 countries in the data set, people in Australia generate more revenue, followed by those in the South West. The Central region had the least revenue.
* In all 10 countries, males generated more income than their female counterparts. 
* When the revenue was compared across each age category, the young adults generated the highest revenue. This is realistic because young adults are the working-age population. Teenagers had zero revenue.







