
# Bike sharing analysis with Ford GoBike Dataset by Eda Sanli

## Dataset

The data consists of information regarding 3.2 million bike rides, including bike_id, duration,start_time, end_time, latitude and longtitude points, rental access method, user type and so on. The dataset can be found in Ford GoBike website here

**Dataset**: (https://s3.amazonaws.com/fordgobike-data/index.html)

Data **time range** is 01/2019 - 03/2020.

The data consisted of 15 different variables as below:

**Numerical variables**: bike_id, duration_sec,end_station_id, end_station_latitude, end_station_longtitude, start_station_id, start_station_latitude, start_station_longtitude,

**Non-numerical variables**: bike_share_for_all_trip, end_station_name, end_time, rental_access_method,start_station_name, start_time, user_type

Unfortunately there has been an update in Ford GoBike website, therefore such interesting variables  like age, gender, etc. have been removed from the dataset. This made the process harder to enrich the scope of the analysis in demographic areas.
![image.png](attachment:image.png)


## Summary of Findings

Since there was a variable scarcity with the new update in the dataset, I checked the different behaviours between user types like subscribers and customers (non subscribers).

- Monthly Bike Ride counts have been slowly developing in 2019 and reached the peak point especially in February 2020. However, we see a huge drop in March 2020, which was not predictable considering the historical trend. 
- Users usually prefer to rent bikes during the week than the weekend. Week days have approximately around 14-15% of the total share, where this number drops to 8-10% during the weekend
- Most rides are taken during the week days, between 7-9 in the morning or 17-19 in the evening.  We can also observe that there a little increase on the lunch time around 12.
- We see a more active evening/night bike rent behavior in the weekend than the week days (12-4 am in the morning seems more active in the weekends than the week days.)
- There is a big gap in customers and subscribers share.  Subscribers make 76% of the total bike rides whereas customers have only 24%
- The gap between subscribers and customers share has almost closed in Dec'19 but then increased again in 2020.
- Subscribers use bike sharing system more strictly at 7-9 and 16-19 whereas it is slightly more fragmented for customers between Monday to Friday.
- Customers use bike sharing system more than subscribers on the weekend. 
- Subscribers take bike trips for short duration (11.4 mins) whereas customers take it for almost twice the duration (19.8 min)
- Similar with trip duration plot, we see different behaviors between user types, where customers use bike sharing system for comparably longer distance trips (2.8 km) than subscribers (2.1 km)
- Subscribers ride 1.5 times faster than customers (and we can hypothetically assume that this is because they use bike rides more functionally, such as daily commuting)
- 91% of the subscribers use app and this share increase to 97% for customers.
- We only have membership data for 70% of the bike rides, 64% of those rides do not belong to a Bike Share For All member.!

## Key Insights for Presentation

For the presentation, I focus on the influence of user type, weekday, hour of the day to highlight the insights. 

I start with a data introduction, data gathering, assessing, cleaning.

In explanatory part, I start by looking at the data on high level, continue by analysing it with various time perspectives and continue with different user type data observations.I tried to make sure that I use different colors for variables to make it neat and clear. 


```python

```
