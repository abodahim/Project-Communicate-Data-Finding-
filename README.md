# Customer habits of [Ford GoBike System](https://www.fordgobike.com/) in 2018


## Dataset

The data consist of approximately 1,85M bike rides in 01 2018. The attributes include the trip start/end time, start/end station, duration in seconds as well as additional information such as user type, gender, and birth date. 155K data points were removed from the analysis due to inconsistencies in the birth date, which in some cases was dated prior 1900. The data can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html), with feature documentation available [here](https://www.fordgobike.com/system-data).


## Summary of Findings

In the exploration, I found that there are two types of clients using the system: subscribers who are mainly daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around the lunch time, and customers, usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and suprisingly.


## Key Insights for Presentation

For the presentation, I focus on customer habits in 2018. Since the Ford GoBike System currently offers 3 subscribtion types: Single Ride, Access Pass (24h or 72h). I start by introducing the split between those who use the system occasionally and those who has a membership. Afterwards, I move to daily and weekly habits of customers. I use the heatmap to show when bikes are high in demand throughout the week. To finish, I introduce the histogram of the trip duration per customer type to further show the differences in renting behaviour.