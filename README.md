# Communicate-Data-Findings-DAND-Udacity
Explore the ford go bike datasets communicate the data findings.

Author:- Sarthak Das Roy

![bike-share-for-all-image](https://user-images.githubusercontent.com/48868854/57011471-6a04db80-6c1f-11e9-9ba5-70ed3b47f1be.jpg)

## Dataset
This document explores the Ford GoBike's trip data for public containing approximately 30,15,214 bike rides from FY2018 and 2017. The attributes included the trip start/end time, as well as additional measurements such as user type, gender, and age. 155K data points were removed from the analysis due to inconsistencies in the birth date, which in some cases was dated prior 1900. The data is available [here](https://s3.amazonaws.com/fordgobike-data/index.html).

## Summary
In the exploration, I found that there are two types of clients using the system: subscribers who are mainly daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around the lunch time, and customers, usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. The bike share system was used more often around summertime (May-October) with a clear drop from January to March, most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and suprisingly, for casual users there are quite a lot of females using the system between January and March in comparison to males (the ratio is much smaller than for the rest of the year).

## Key insights
There were 3.31 billion rides. 20-30 years old users are rapidly growing compared to other user groups. When the service first started 30-40 years old users were dominant, however 20-30 years old users became leader in a year. 20 to 40 years old people took the more than 70% of bike rides. Among those, 30 to 40 years old people's rides account almost 40% of all bike rides. Male took around 76% of all bike rides, and female took around 24% of them. People use this service on weekdays more than weekends. 8am and 5pm are the peak hours for this service. Also, people use this service when they are in lunch time as well. Percentage of subscribers is almost 88.15%. Percentage of customers is almost %11.85. Customers' rides seems increasing slightly but subscibers' rides reached 6 times more than customers' on October 2018. There is a decrease on November 2018 for subscribers but it seems like it is related with winter season. Subscribers' average trip duration is around 11 minutes. Customers' average trip duration is around 28 minutes. Subscribers and customers trip distance were about the same, which is slightly more than one mile. 90% of bike rides take place on weekday. The peak bike rides time for all members is around commute time.

Finally, it seems that 40 to 50 years old age group use the service the most. After Ford GoBike did a pilot launch of e-bike on April 24th 2018, there have been quite a lot of electric bike rides as well, which reached to 10% of daily rides at the end of July 2018. However, daily electric bike rides is on downward trend.

## Presentation
For the presentation, I focus on customer habits in 2018. Since the Ford GoBike System currently offers 3 subscribtion types: Single Ride, Access Pass (24h or 72h) and Monthly Membership, I start by introducing the split between those who use the system occasionally and those who has a membership. Afterwards, I move to daily and weekly habits of customers. I use the heatmap to show when bikes are high in demand throughout the week. To finish, I introduce the histogram of the trip duration per customer type to further show the differences in renting behaviour.
