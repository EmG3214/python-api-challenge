# python-api-challenge
A project about weather and lattitudes and planning vacations based on weather patterns. 

WeatherPy:
We start by gathering a list of random cities, then we retrieve weather data for these cities from the weather API.
We save this data to a file for the Hotel planning portion.
Before moving on, we look at the relationships between the weather and lattitude for the different hemispheres.
You can find scatterplots and regression plots and analyses in the Jupyter notebook itself.
 
VacationPy
We take the city weather data we exported and map the cities with the point size being humidity.
Then, I narrowed down the data to my ideal temperature, cloudiness, wind speed, and humidity.
I cleaned up the data and then created a Dataframe of just the columns we would need for the next step.
We used the longitude and latitude to call the geoapify API to find the closest Hotel, within 10km. 
We then mapped the resulting ideal cities with additional hover information. 

