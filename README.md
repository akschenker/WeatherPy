# WeatherPy

This was a homework assignment for the UC Berkeley Data Analytics bootcamp. For this assignment, we were asked to determine whether various features of the weather change as latitude approaches the equator. To accomplish this task, I created a uniform distribution of latitudes and longitudes, used the `citipy` library to locate the name of the closest city to those coordinates, then queried the Open Weather Map API to find current weather data for each of those cities. 

It was found that only temperature reliably changes as latitude approaches the equator, as to be expected. Cloudiness, wind speed, and humidity have no relationship with latitude.


## Prerequisites

Data is requested from the [Open Weather Map API](https://openweathermap.org/). To run, add a `config.py` file with your own API key. The notebook should be run in an Anaconda 3 environment.

The third-party library [citipy](https://github.com/wingchen/citipy) is also required to run the notebook. Instructions for installation can be found at the above link.

## Built With

* Jupyter Notebook
* Pandas
* NumPy
* Requests
* Matplotlib Pyplot

## Authors

* Arley Schenker
