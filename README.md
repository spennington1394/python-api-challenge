Analysis of climate at the equator.

Data: data comes from OpenWeatherMap API and utilizes python library citipy to collect a list of 593 cities and weather data about the cities including: cloudiness, humidity, latitude, longitude, maximum temperature, wind speeds, and country.  The collected API data was then exported as a csv file for further analysis. 

Step 1: 

Set dependencies: matplotlib, pandas, numpy, requests, time, scipy.stats, and citipy in a jupyter notebook. 

Step 2:

Utilized citipy to collect a list of 593 cities closest to the equator.  Then used the list of cities to query OpenWeatherMap API collecting information about the cities. 

Step 3: 

Created and exported a cleaned dataframe as a csv file to do further analysis on in another jupyter notebook. 

Step 4:

Used the newly created dataframe to create scatter plots showing the maximum temperature, humidity, wind speed in comparision to latitude.  Then ran a linear regression on max temperature and latitude to see what correlation was observed between cities in the northern hemisphere and southern hemisphere. The linear regression information was placed on top of the previously mentioned scatter plots. 

Step 5: 

Read in the previously exported csv into a jupyter notebook and set dependencies. 

Step 6: 

Put conditionals on several columns in dataframe to determine where is the "ideal" place to vacation.  Then utilize Google API to find hotels in cities utilizing the latitude and longitude columns in the dataframe. 

Step 7:

Took the hotel data and created a visualization using gmaps. 

