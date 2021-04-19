# surfs_up

## Project Overview
The scenario in this project is that the year is 2017 and you want to open a shop that sells both ice cream and surf apparel in Oahu, Hawaii. There are interested investors, but in order to convince them that this shop will be profitable year-round, you are asked to do an analysis of the weather in Oahu. One investor, W. Avy provides you with a SQLite database with the weather information in Oahu from 2010 through August 2017.

To make it clear that the year-round weather in Oahu makes it a great location for your shop, you decide to first look at weather data from June and from December, as they are traditionally the hottest and coldest months of the year, respectively. 

Eventually, W. Avy and you will present your findings to their board of directors. Since the board is not interested in directly reading your code, you decide to make a website for them to easily filter through your analysis- reflected in the climate_analysis file.

## Results
The results look promising because they support your position that Oahu is the perfect location for this shop based on temperature.

### June Results
The image below describes the provided June weather data.

Three key takeaways from these statistics are:
* The mean temperature in Oahu in June is 74 degrees farenheit with a standard deviation of 3.3. This is the kind of weather where most people want to be active and outside- especially in the sun!
* The max temperature recorded in June from 2010-2017 is 85 degrees farenheit. This is also good news because it is definitely hot outside, but not too hot where people are too lethargic to do anything due to fatigue from the heat.
* The minimum temperature is only 64 degrees, which is still plenty warm to be outside and this minimum is not significantly colder than the average temp, which demonstrates stable temperatures.

![june.png](https://github.com/asliwinski23/surfs_up/blob/main/june.png)

### December Results
The image below descibes the provided December weather data.

Three key takeaways from these statistics are:
* The average temperature in December is only 3 degrees farenheit colder than in June, 71 degrees, with a standard deviation of 3.7. This means people are most likely outside year-round because the average temperature is in the mid-to-low-seventies.
* The max temperature recorded in December from 2010-2017 is 83 degrees farenheit. This is only two degrees colder than the maximum temperature recorded in June- that's great news!
* Unfortunately, in December a minimum temperature of 56 degrees farenheit has been recorded. This is not ideal for walking around outside, let alone wanting to think of ice cream or surfing. Luckily, this low temperature does not appear to be common at all, as only 25% of the recorded December data falls below 69 degrees. 

![december.png](https://github.com/asliwinski23/surfs_up/blob/main/december.png)

## Summary
This June and December weather analysis will definitely boost investor confidence in the ice cream and surf shop because the numbers not only prove that the weather is consistently warm in Oahu, but the temperature does not vary by much, not even between opposite seasons!

I think it would certainly make sense to repeat this analysis for the other 10 months of the year, but two additional queries we could have performed in this June and December analysis are:
* creating a frequency histogram for the recorded temperatures. This would help visualize that temperatures like the minimnum recorded temperature in December (56 degrees) is a bit of an outlier.
* looking at the other weather data categories provided, such an rainfall by date. While it is great that the weather is usually warm enough to be outside in Oahu, this does not account for weather conditions that may want to make people stay inside, such as rain or wind.
