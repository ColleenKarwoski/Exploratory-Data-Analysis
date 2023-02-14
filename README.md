# project1-group2

This repository contains an exploratory data analysis of used car sales in the US between the years 2018 and 2020. As a group, our objective was to find answers to the following three questions:

REASONS WHY WE FOUND QUESTIONS INTERESTING/WHAT MOTIVATED US TO ANSWER THEM!!!

1. What specifications of a vehicle appear to have the largest impact on price?
2. What is the most commonly seen price point for certain vehicles?
3. How does the value of vehicle change over time? And is there any statistically significant differences between the trends of different makes and models?

To find the answers to these questions, we used data from a US used car sales CSV file found on Kaggle (the original CSV as well as a CSV containing the cleaned version of the data set can be found within the Resources folder of this repository entitled "used_car_sales.csv" and "cleaned_used_car_data.csv" respectively).

![alt text](https://github.com/DanielPapp3/project1-group2/blob/main/Images/Original%20Dataset.PNG)

The original data set (pictured above) had some issues that we cleaned up in the final data set including non-numerical zip codes and unusual price and mileage values. We eliminated zip codes that contained non-numerical characters and ensured that the remaining codes matched a record of US zip codes using a database maintained by the USPS (can bev found at - https://postalpro.usps.com/ZIP_Locale_Detail or in the Resources folder of this repository). We also eliminated records for vehicles that were sold for less than $100 or had more than 400,000 miles. The resulting data set is pictured below.

![alt text](https://github.com/DanielPapp3/project1-group2/blob/main/Images/Cleaned%20Dataset.PNG)

The results of our exploratory data analysis showed that after controlling for the make and model of the vehicle, age and mileage explained a respectable amount of the variation in the prices of different vehicles. One model that showed a particularly strong correlation was ???. In that case roughly ???% of the price variance could be explained by mileage and ???% by age. Below is a scatter plot showing the correlation for mileage and age for the ???.

[INSERT PLOTS HERE]

The most common price point for vehicles varied wildly across different makes and models (as shown by the long tail of the histogram depicted below). Some of the most budget friendly options included ???, ???, and ???, while ??? held some of the most expensive used vehicles on average.

[INSERT HISTOGRAM HERE]

Based on this exploratory data analysis we were unable to find any consistently explanable differences between the price trends of different makes and models over time. With the exception of some cars that are considered collectors items/vintage, most vehicles saw their value dwindle over time at a fairly similar rate.
