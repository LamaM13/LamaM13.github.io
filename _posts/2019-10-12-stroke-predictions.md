---
layout: post
title: Stroke Prediction Using Classification Methods
---

### Overview

According to the *World Health Organization*, Stroke is the second leading cause of death worldwide after Ischaemic heart disease. Ischaemic heart disease and stroke are the world's biggest killers, accounting for a combined 15.2 million deaths in 2016. 

### Objective 

The main objective of this project is to predict whether an individual has a stroke or not based on many features that might be largely preventable risks such as smoking and hypertension.

-----

### Work Stages

#### Data Acquisition 

Data was acquired from *Kaggle.com*, [Here is the link](https://www.kaggle.com/asaumya/healthcare-dataset-stroke-data). 
The data set includes almost 35,000 of observations. 

#### EDA 

As we see here there is an imbalanced class in the target, there are only 548 individuals with stroke, while 98% of individuals are not having a stroke, and this issue was solved by using SMOTE to oversample positive values. 

![image info]({{site.url}}/images/target's_classes.png)

The first plot shows the number of people who have hypertension and those who did not have hypertension with a stroke or not. The second plot shows the age of these individuals.

![image info]({{site.url}}/images/hypertension1.png)
![image info]({{site.url}}/images/hypertension.png)

The first plot shows the number of people who have had heart disease and those who did not have heart disease with a stroke or not. The second plot shows the age of these individuals.

![image info]({{site.url}}/images/heart1.png)
![image info]({{site.url}}/images/heart2.png)

The first plot shows the number of individuals and their smoking status who had stroke or not, and the second plot shows the ages of these individuals. 

![image info]({{site.url}}/images/smoke1.png)
![image info]({{site.url}}/images/smoke2.png)


#### Baseline Model


#### Reult 
<!-- 
Extract __top ten crowded__ stations and do the following:

* Top five crowded stations by <span style="text-decoration: underline">number of exits</span>
* Look for the most <span style="text-decoration: underline">crowded days</span>
* Look for the most <span style="text-decoration: underline">crowded times</span>
* Look for the most <span style="text-decoration: underline">crowded turnstiles</span>

--- 

Look for the stations near LAGUARDIA and JFK airports:
* After extracting the most crowded stations the airport stations weren't part of them. 


##### Top Ten Stations by # of Exits
![image info]({{site.url}}/images/top_ten_stations.png)

##### Crowded Days In The Week 
![image info]({{site.url}}/images/crowded_days.png)

##### Crowded Times In The Day
![image info]({{site.url}}/images/crowded_times.png)

##### Top Turnstiles by # of Exits 
![image info]({{site.url}}/images/most_turnstiles.png)
 -->