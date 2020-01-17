# WeatherPy - API Challenge 

OpenWeatherMap is an online service that provides weather data, including current weather data, forecasts, and historical data. The data analysis and visualization shows the weather of 500+ cities across the world of varying distance from the equator. To accomplish this,
i am utilizing a simple Python library, the OpenWeatherMap API.


* [Background](#background)
* [Observable Trends Based on the Data](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, I signed up for OpenWeatherMap and got the key to use OpenWeatherMap API data. To get the OpenWeatherMap API Data URL used can be found [here](http://api.openweathermap.org/data/2.5/weather?"). With units = "imperial".


## <a name="trends"></a>Observable Trends Based on the Data

These were the key insights I found in my analysis:

1. As latitude increase or decreases from around the 0-20 degree range of latitudes,the temperature decreases. 

2. In particular 20-40 degrees, appears to be the most humid part of the world.

3. No matter where you are, on any given day, it could be cloudy. 

4. No matter where you are, on any given day,the average wind speed is observed between 0 to 15 (mph).
I used basic Pandas methods and functions to do my analysis and matplotlib for Visualization.

Final Report includes Scatter plots for:

1. Temperature (F) vs. Latitude
2. Humidity (%) vs. Latitude
3. Cloudiness (%) vs. Latitude
4. Wind Speed (mph) vs. Latitude

 ##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/API-Challenge/blob/master/WeatherPy/starter_code/WeatherPy.ipynb>
The notebook is also available inside this repository [here](./WeatherPy/starter_code/WeatherPy.ipynb).

##  <a name="technologies"></a>Technologies Used

* Python
* Pandas library
* Matplotlib library
* Jupyter Notebook