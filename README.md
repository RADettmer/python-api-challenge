# python-api-challenge
python-api-challenge
What's the weather like?

This challenge includes using APIs from OpenWeather and Google Maps. Please be advised, to run this code you will need an API Key from each source.

WeatherPy file includes code to collect over 500 latitude and longitude coordinates to generate a city list. From this list, weather data is collected from OpenWeather and the cities that there isn't any weather information are dropped from the data frame. The completed data frame is saved in a csv file called output_data.

Several graphs are generated from this data frame to compare latitude to temperature, humidity, cloudiness and wind speed. These graphs are saved as separate files.

VacationPy file includes code to narrow down a vacation location given specific conditions using the output_data csv file generated above.  Once specific locations are generated, a new data frame was created to find hotels nearby Google Maps. For locations not having a hotel are removed from the data frame and a heat map is generated for the final locations.

Included are two maps. The heatmap shows all locations generated. The hotelmap shows the hotel loctations determined by the vacation conditions.
