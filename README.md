# Citibike Bikesharing
## Purpose of the Analysis
The purpose of this analysis is to evaluate NYC Citibike usage data to identify patterns and potential utilization in Des Moines, IA

## Resources
NYC Citibike usage for August 2019 was evaluated. The source of the data can be found here: [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)

Some visualizations were created using the original csv file, but the majority of the visualizations were created using a file transformed using the following file: [NYC_CitiBike_Challenge.ipynb](https://github.com/MDHetrick/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

All visualizations were created with tableau public and the story can be found at the following website: [CitibikeAnalysis](https://public.tableau.com/app/profile/melea.hetrick/viz/bikesharing_16493796263470/CitibikeAnalysis)

## Results

![image](https://github.com/MDHetrick/xxx.png)

**Checkout Times for Users:** The vast majority of trips lasted less than one hour, with a peak at 5 minutes (146,752 trips) followed by a decrease in number of trips until a trip length of greater than 3 hours, where the number of trips are generally less than 10 for any trip length. 

![image](https://github.com/MDHetrick/xxx.png)

**Trips by Weekday Per Hour:** The heaviest usage times during the week are 8-9am and 5-7pm, with Thursdays between 5 and 7pm being the heaviest usage during this timeframe and Wednesday and Friday 5-7 being lowest usage during this timeframe. On the weekends, there is not a concentrated usage pattern, but midday (about 10am-5pm) shows more usage than evenings and mornings. 

![image](https://github.com/MDHetrick/xxx.png)

**Mean Trip Duration by Birth Year:** The birth years reported range from 1885 and 2003. Because the oldest living person alive in 2019 was born in 1903, all birth years earlier than 1903 can be excluded. With this data excluded, there is a slight increase in mean trip duration as birth year increases, especially with birth years after 1945. There is a spike in trip duration for the birth year 1969.

![image](https://github.com/MDHetrick/xxx.png)

**Gender Breakdown:** In August 2019, males accounted for about 65% of the trips, females accounted for about 25% of the trips, and those with an unknown gender accounting for about 10% of the trips.

![image](https://github.com/MDHetrick/xxx.png)

**Checkout Times by Gender:** Following similar patterns to the general gender breakdown and checkout times for users visualizations, males accounted for the majority of the trips with a peak checkout time of 5 minutes (108,087 trips). Females accounted for the second highest number of trips peaking at 6 minutes (34,151 trips). Trips taken by those with unknown gender peaked at 11 minutes (7,389 trips), however this curve is far flatter than the male and female curves.

![image](https://github.com/MDHetrick/xxx.png)

**Trips by Gender (weekday per Hour):** Following similar patterns to the general gender breakdown and trips by weekday per hour visualizations, heaviest usage times during the week are 8-9am and 5-7pm, with Thursdays between 5 and 7pm being the heaviest usage during this timeframe and Wednesday and Friday 5-7 being lowest usage during this timeframe. On the weekends, there is not a concentrated usage pattern, but midday (about 10am-5pm) shows more usage than evenings and mornings. Males account for heaviest usage, followed by females, and then unknown gender.

![image](https://github.com/MDHetrick/xxx.png)

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
