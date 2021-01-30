# python-api-challenge
There are two folders within this particular API project, WeatherPy and VacationPy. The purpose is to evaluate the weather conditions in relation to the latitude and determine ideal vacation locations and corresponding hotels in the given cities. 

## Technologies
Data was pulled from the OpenWeather API and Google Maps APIs to generate random cities and determine weather and visualize on a map. Matplitlib was used in combination with pandas in the python script and generated through jupyter notebooks, this allowed for ease of edit, update, and viewing of the weather and map data.

## WeatherPy
The WeatherPy notebook selects and details cities and the weather data using the weather API. Using that to then plot various scatter plots and linear regressions between latitude and a variety of variables. Further analyzing then between the two hemispheres, northern and southern, based on the latitude and the given variables. 

Two separate folders were made to show the respective scatter plots and linear regressions that resulted from the data.

The corresponding observable trends observed within this report are detailed at the bottom of the jupyter notebook.

## VacationPy
The VacationPy notebook takes the given city weather and location data from the WeatherPy notebook and, using gmaps, plots it in a heat map based on humidity. After filtering the cities for ideal weather conditions and then locating the nearest hotels within a 5000 meter radius, I added markers to the heat map to indicate the locations of the hotel and the correspinding city and country. 
