# Bike Sharing Exploration
## by Osama Adel


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data consists of 183412 rides and 16 variables of 4646 bikes over the period of one month (from 1 Feb 2019 to 1 March 2019) from and to 329 stations. The data has no duplicates but has some missing values in the start station, end station, gender and birthdate variables.

## Summary of Findings

* The duration distribution is very very right skewed, with some trips reaching above 85000 seconds. However, the majority of trips took between 62 and 2000 seconds, with the average at 726 seconds. Plotting the duration on a log scale shows that it follows a normal distribution slightly right skewed.
* I would say that there is a repetitive pattern in the starting time from 5-9 Feb and 19-24 Feb. Also, the number of rides reached its maximum by the end of the month. In general, the number of rides seem to increase over the days.
* The distribution is left skewed which means more of the younger generations from 1980 to 2000 are using the bike sharing service than older generations.
* Okay, so there are users who registered their birth year before 1940, which means they were over 80 years old when the data was collected ! Moreover, there are 54 users who registered they were born before 1901 !!! Clearly, some of these values are incorrect.
* The day with the highest number of rides is Thursday followed by Tuesday and Wedensday. The days with the least number of rides are in the weekeend: Saturday and Sunday. Maybe rides are made to and from work.
* The hour of day distribution shows a bimodal distribution with one peak from 8 to 10 AM and another from 4 to 6 PM. Maybe these are the rush hours of the day.
* About 20000 users are customers and 160000 are subscribers.
* The majority of members are males (about 130000 users) followed by females (about 40000 users) and then others.
* The points shows a wider variation in duration taken for younger users than older users. In short, older users seem to take smaller rides than younger users.
* From the 2D histogram, it is clear that most rides take place around 8-9 AM and 5-6 PM. Also the duration of rides that happen in the evening take slightly longer than those of the morning. There are also some rides in the middle from 10 AM to 3-4 PM, but almost non before 5 AM.
* It is clear that in working days (from Monday to Friday), the start time of a ride is concentrated around 8-10 AM and 5-7 PM however, in weekend, the distribution is normal peaked at the middle of the day at around 3 PM.
* The distribution of the duration is slightly wider in the weekend than the working days.
* Age doesn't affect the start hour of the ride.
* Customers on average take longer rides than Subscribers.
* Males, Others and Femals take rides of almost the same length.
* Rides with no bike share for all trip take longer on average than those with share for all trip.
* Males, Females and others have almost the same distribution of start hour.
* There is almost no difference in the start and end hours for customers and subscribers.
* Females seem to take rides slightly earlier than males and others.
* Customers seem to take longer rides than subscribers throughout the week especially in weekends.


## Key Insights for Presentation

* The distribution of duration especially on a log scale is normal.
* The distribution of the rides over the days of the week.
* The distribution of birth years of users.
* The ratio of subscribers and customers. The counts are turned into percenteges in the presentations.
* The ratio of males, females and others. The counts are turned into percenteges in the presentations.
* The distribution of starting hour per each day of the week.
* The effect of user type (customer or subscriber) on duration.# bike_sharing
