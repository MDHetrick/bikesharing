# Citibike Bikesharing
## Purpose of the Analysis
The purpose of this analysis is to evaluate NYC Citibike usage data to identify patterns and potential utilization in Des Moines, IA

## Resources
NYC Citibike usage for August 2019 was evaluated. The source of the data can be found here: [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)

Some visualizations were created using the original csv file, but the majority of the visualizations were created using a file transformed using the following file: [NYC_CitiBike_Challenge.ipynb](https://github.com/MDHetrick/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

Visualizations were created with tableau public and added to a story which can be found at the following links: 
- [Citibike Analysis](https://public.tableau.com/app/profile/melea.hetrick/viz/bikesharing_16493796263470/CitibikeAnalysis) 
- [Citibike Analysis Alternate link](https://public.tableau.com/views/bikesharing_16493796263470/CitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

Links to individual visualizations created for the challenge: 
- [Checkout Times for Users](https://public.tableau.com/views/bikesharing_checkout_times/CheckoutTimesforUsers?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 
- [Trips by Weekday Per Hour](https://public.tableau.com/views/bikesharing_trips_by_weekday_per_hour/TripsbyWeekdayPerHour?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- [Checkout Times by Gender](https://public.tableau.com/views/bikesharing_checkout_times_by_gender/CheckoutTimesbyGender?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- [Trips by Gender (weekday per Hour)](https://public.tableau.com/views/bikesharing_trips_by_gender_weekday_per_hour/TripsbyGenderWeekdayPerHour?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- [User Trips by Gender by Weekday](https://public.tableau.com/views/bikesharing_user_trips_by_gender_weekday/UserTripsbyGenderbyWeekday?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

Links to individual visualizations created in the module and included for analysis: 
- [Mean Trip Duration by Birth Year](https://public.tableau.com/views/bikesharing_trip_duration_birth_year/MeanTripDurationbyBirthYear?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)*
- [Gender Breakdown](https://public.tableau.com/views/bikesharing_gender_breakdown/GenderBreakdown?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)*
## Results
### Checkout Times for Users

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trip_duration.png)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trip_duration_h0.png)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trip_duration_h1h2.png)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trip_duration_h2h10.png)

**Checkout Times for Users:** The vast majority of trips lasted less than one hour, with a peak at 5 minutes (146,752 trips) followed by a decrease in number of trips until a trip length of greater than 3 hours, where the number of trips are generally less than 10 for any trip length. 

### Trips by Weekday Per Hour

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trips_by_weekday_per_hour.png)

**Trips by Weekday Per Hour:** The heaviest usage times during the week are 8-9am and 5-7pm, with Thursdays between 5 and 7pm being the heaviest usage during this timeframe and Wednesday and Friday 5-7 being lowest usage during this timeframe. On the weekends, there is not a concentrated usage pattern, but midday (about 10am-5pm) shows more usage than evenings and mornings. 

### Mean Trip Duration by Birth Year

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/mean_trip_duration_by_birth_year.png)

**Mean Trip Duration by Birth Year:** The birth years reported range from 1885 and 2003. Because the oldest living person alive in 2019 was born in 1903, all birth years earlier than 1903 can be excluded. With this data excluded, there is a slight increase in mean trip duration as birth year increases, especially with birth years after 1945. There is a spike in trip duration for the birth year 1969.

### Gender Breakdown

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/gender_breakdown.png)

**Gender Breakdown:** In August 2019, males accounted for about 65% of the trips, females accounted for about 25% of the trips, and those with an unknown gender accounting for about 10% of the trips.


### Checkout Times by Gender

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/checkout_times_by_gender.png)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/checkout_times_by_gender_h0.png)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/checkout_times_by_gender_h1h2.png)

**Checkout Times by Gender:** Following similar patterns to the general gender breakdown and checkout times for users visualizations, males accounted for the majority of the trips with a peak checkout time of 5 minutes (108,087 trips). Females accounted for the second highest number of trips peaking at 6 minutes (34,151 trips). Trips taken by those with unknown gender peaked at 11 minutes (7,389 trips), however this curve is far flatter than the male and female curves.

### Trips by Gender (weekday per Hour)

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/trips_by_gender-weekday_per_hour.png)

**Trips by Gender (weekday per Hour):** Following similar patterns to the general gender breakdown and trips by weekday per hour visualizations, heaviest usage times during the week are 8-9am and 5-7pm, with Thursdays between 5 and 7pm being the heaviest usage during this timeframe and Wednesday and Friday 5-7 being lowest usage during this timeframe. On the weekends, there is not a concentrated usage pattern, but midday (about 10am-5pm) shows more usage than evenings and mornings. Males account for heaviest usage, followed by females, and then unknown gender.

### User Trips by Gender by Weekday

![image](https://github.com/MDHetrick/bikesharing/blob/main/Visualizations/user_trips_by_gender_by_weekday.png)

**User Trips by Gender by Weekday:** In general, male and female subscribers are more likely to utilize this service, while those of unknown gender were more commonly customers not subscribers. Of customers, Saturdays and Sundays are the days with heaviest usage. Of subscribers, Thursday is the day of the week with heaviest usage and Sundays and Wednesdays are the days with the lowest usage.


## Summary
#### Summary of Current Visualizations
Overall patterns of August citibike utilization in NYC show the following:
- Males utilized the service more than females or those with unknown genders
- The majority of rides lasted less than one hour
- Subscribers utilized the service more often than non-subscribers
- Weekdays during tyical commute times have the highest utilization for male and female subscribers while non-subscribers of any gender have the highest utilization on Saturdays and Sundays.
#### Additional visualizations
With the current data, the following visualizations would be useful:
- Filter the Mean Trip Duration by Birth Year visualization by gender and usertype which will allow us to better understand some of the anomalies in the data.
- Filter the top start and end locations by day of week and possibly customer vs subscriber which will provide information about optimal locations that can be applied to other cities.
