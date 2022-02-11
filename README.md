# python-api-challenge


     ATTENTION GRADER: I received numerous emails this evening stating "GitGuardian has detected the following Google API Key exposed within your GitHub account." Therefore, I deleted my currently active API key that I previously stored in my api_keys.py file (aka g_key in this Notebook). If you do not have one that you can use, please let me know (brian.zdarsky@gmail.com) and I will create a new one and update my api_keys.py ASAP. Sorry for the inconvenince, but I do not know the impact yet and I have heard how some have been charged $300,000...and I can't afford that:( Thank you, Brian


My work can be found at https://github.com/BZNUDS/python-api-challenge
    Jupyter Notebook Files: WeatherPyFinal.ipynb and VacationPyFinal.ipynb
    Output data file and .png plots: WeatherPy/output_data
    Analysis will be incorporated into the Jupyter Notebook (Still WIP)
    
The goal of this challenge to take what I've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

It is broken down into 2 parts, Part I - WeatherPy and Part II - VacationPy

Part I - WeatherPy 

The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.
The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, take the time to explain what the linear regression is modeling. For example, describe any relationships you notice and any other analysis you may have.
Your final notebook must:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Complete analysis using a Jupyter notebook.
Must include a written description of three observable trends based on the data.


Part II - VacationPy

Using my skills in working with weather data, plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment. This includes:

Create a heat map that displays the humidity for every city from Part I.
Narrow down the DataFrame to find your ideal weather condition. 
Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

Must include a screenshot of the heatmap you create and include it in your submission.




