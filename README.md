# python-api-challenge

3 observable trends in WeatherPy and VacationPy:

1. In WeatherPy, the cities randomly selected were scattered around the world. From the scatterplots, there are some expected trends, such as cities closest to the equator (Lat = 0) are generally warmer than those further away. 
However, there is a cluster of cities around Lat 20 degrees which are currently warmer than those cities near the equator. This could be because it is currently summer in those cities (i.e. in the Northern Hemisphere) and they
may be experiencing warmer days as a result. There appears to be little correlation between latitude of a city and humidity, wind speed, and cloudiness. 

2. In considering the ideal climate for a vacation, I have used the following parameters:
	a. Temperature between 24 and 29 - warm days but not too hot or too cool
	b. Humidity levels between 30% and 60% - based on research, this is the most comfort level to be outdoors
	c. Wind Speed of below 9mph - based on research, this is a comfortable level to be fairly sedentary (e.g. sitting) outdoors
	d. Cloudiness of 0% - for beautiful sunny days

The majority of cities identified were fairly close by the equator, supporting the observation from WeatherPy analysis that there may be cities further from the equator which is hotter than those near the equator. 
The majority of the cities were also in the Southern Hemisphere. As it is winter in the Southern Hemisphere, the maximum temperature may be more favourable to the parameters for a perfect vacation.

3. There are limitations to identifying cities for vacations using this method. For example:
	a. The analysis is conducted on weather statistics as at a particular day. If a city is experience a heatwave or a cold snap, it may not be representative of its normal weather patterns. A longer period of data should be
	   taken into consideration to identify trends and likelihood of ideal vacation climate.
	b. The cities identified as ideal vacation spots does not take into account the desireability of the location. Based on the climate parameters I selected, the cities identified may not be suitable for travel due to various 
	   reasons such as geopolitical instability, lack of suitable recreation activities. 
