---
layout: post
title: Predicting Hotels Rating 
---

### Overview 
*Booking.com* is a world leader in booking accommodations online. It acts as the intermediary between properties that want to sell their rooms and guests that are looking for accommodation.

---
### Case Study Problem 
In this problem, I want to find out the factors that influence the ratings of hotels listed on *booking.com* website, so as to be able to predict the future ratings of hotels or by applying linear regression. To achieve this goal, I will specifically focus on the hotels listed in Dubai, Abu Dhabi, Sharjah, Riyadh and Jeddah. 

----
### Methodology

#### Gathering Data
- Web-scraped Booking.com lisiting hotels 
- Tools: Beautiful Soup and Selenium

#### Data Cleaning 
- Slice number part from string and convert its type from string to numeric data type.
- Filling the missing data with zeros excpet the missing data of features 'number of bedrooms' and 'number of bathrooms' it was filled with ones.

#### Exploatory Data Analysis 
- Plot pairs was created to see how data are distributed. 
- Heat map was created to see the most related features to target. 

#### Moedling and Building Baseline 
- The categorical data was handled by creating dummy variable. 
- Split the data into two sets, one for the training set and the other for the testing set.
- Cross-validated the model. 

#### Testing 
- Test the model. 

### Features Selected 
- City 
- Price of hotel 
- Number of bedrooms 
- Number of bathrooms 
- Bed type
- Cancellation Policy 

### Correlation Matrix 

![image info]({{site.url}}/images/heatmap.png)

*The most related features to the target are Hotel_price and Cancellation_policy*

### Result 

![image info]({{site.url}}/images/risduals_and_QQ.png)  


![image info]({{site.url}}/images/result.png)

The R^2 vaalue is: **0.452** 
