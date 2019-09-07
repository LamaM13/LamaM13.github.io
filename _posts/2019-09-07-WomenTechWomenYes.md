---
layout: post
title: WomenTechWomenYes (WTWY) Project
---

*WomenTechWomenYes (WTWY)* has an annual gala at the beginning of the summer each year. As they’re new and inclusive organization, they try to do double duty with the gala both to fill their event space with people passionate about increasing the participation of women in technology, and to concurrently build awareness and reach. To this end they place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to their gala.

-----

### Overview

*(WTWY)* wanted from us to analysed the MTA subway data, to help them optimize the placement of their street teams, such that they can gather the most signatures, ideally from those who will attend the gala and contribute to their cause. 
As we are a Data Scientist team, we conducted an EDA on MTA data set to get insights on the data for *(WTWY)'s* purpose. 

-----

### Work Stages

#### Data Cleaning
 - Strip White Spaces.
 - Assure there is no NaN values.
 - Extract the actual from **Entries** and **Exits** values. 
   1- Replace the negative values by zero. 
   2- Set a limit for the **Entries** and **Exits** values. 
 - Parse data and time columns to timestamp.

#### Data Processing 

Extract __top ten crowded__ stations and do the following:

* Top five crowded stations by <span style="text-decoration: underline">number of exits</span>
* Look for the most <span style="text-decoration: underline">crowded days</span>
* Look for the most <span style="text-decoration: underline">crowded times</span>
* Look for the most <span style="text-decoration: underline">crowded turnstiles</span>

--- 

Look for the stations near LAGUARDIA and JFK airports:
* After extracting the most crowded stations the airport stations weren't part of them. 


##### Top Ten Stations by # of Exits
![image info]({{site.url}}top_ten_stations.png)

##### Crowded Days In The Week 
![image info](Users/khalidalsuwayan/Desktop/LamaM13.github.io/_posts/crowded_days.png "Image Description")

##### Crowded Times In The Day
![image info](Users/khalidalsuwayan/Desktop/LamaM13.github.io/_posts/crowded_times.png "Image Description")

##### Top Turnstiles by # of Exits 
![image info](Users/khalidalsuwayan/Desktop/LamaM13.github.io/_posts/most_turnstiles.png "Image Description")
