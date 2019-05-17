# OpenWeatherMap_API

In this project I used the Open Weather Map API and wrapper to find if there is any correlation between a city's latitude and its weather trends.

I started in pandas by creating 1500 randomly generated latitude and longitudes and zipping them together. I then used citipy to find the
closest city to each of the coordinates and generated a master city list. Only unique cities were added to the list. From citipy I also
the country codes for each city. I then created a dataframe with this basic information and used the open weather map API wrapper to get
temperature, humidity, cloudiness, and wind speed for each city. Lastly, I used the populated dataframe to create charts for each
weather characteristic using matplotlib.
