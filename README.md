# WeatherPy

## Project Description: 
This project is an analysis of global weather changes in relation to latitude for over 500 random cities. The OpenWeather Rest API and Python, Pandas, and Jupyter Notebook were utilized to (1) perform API calls and (2) create non-duplicate summary statistics. Matplotlib was used to create scatterplots of each relationship.

![image](https://user-images.githubusercontent.com/51388767/70867428-6b331080-1f43-11ea-877c-991a7a1bae11.png)

![image](https://user-images.githubusercontent.com/51388767/70867932-1befde80-1f49-11ea-9a16-82c8706cb37a.png)

![image](https://user-images.githubusercontent.com/51388767/70867738-a4b94b00-1f46-11ea-84db-8980a02d5dc3.png)

![image](https://user-images.githubusercontent.com/51388767/70867797-7720d180-1f47-11ea-8b30-5b8f6e57c02c.png)


## Observable Trends:

Observations and plot titles will need to be updated with each API call/code run as these trends are from the 8/11/19 evening run.

Five hundred eighty two cities were randomly generated by the API calls.

Of the four weather conditions (maximum temperature, humidity, cloudiness, & wind speed) in this sample, maximum temperature & cloudiness are signaling a near-normal distribution with skewness between -0.5 & +0.5 when all the datapoints are considered.

Every city in the dataset has a positive maximum temperature. However, if someone wanted to cool off on 8/11/19, Argentina might have been the place to be with three of the four coldest cities (Rio Gallagos, Mar del Plata, & Ushuaia) 32 degrees Fahrenheit or below.

Although in very different geographies, Ahipara, New Zealand & Bandarbelya, Somalia have kite flying wind speeds above 30 mph.


## Notes:
At https://openweathermap.org/api simply sign up for a free API key.
Once you receive that API key, copy and paste it within the parentheses in the api_keys.py file.
Open Jupyter Notebook or Jupyter Lab.
Install all the necessary modules to run the code locally.
The results should display as each cell of code runs. 
  

