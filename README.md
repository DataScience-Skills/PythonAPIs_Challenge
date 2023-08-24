## Analysis of Global Weather Patterns

### Tools/Techniques Used:
- **Python:** Utilize Python programming language to handle data manipulation, analysis, and visualization tasks.
- **Jupyter Notebooks:** Use Jupyter notebooks for code development, data exploration, and visualization.
- **citipy Python Library:** Utilize citipy to find the nearest city based on coordinates.
- **OpenWeatherMap API:** Retrieve weather data for cities using the OpenWeatherMap API.
- **Geoapify API:** Utilize the Geoapify API to find nearby hotels for each city.
- **geoViews Python Library:** Create map visualizations of cities and hotels.
- **Data Analysis:** Analyze relationships between weather variables and latitude through scatter plots and linear regression.
- **Data Visualization:** Create visualizations to showcase weather patterns and vacation planning.

__Purpose:__ The purpose of this project is to utilize Python coding skills, data analysis techniques, and APIs to answer a fundamental question: "What is the weather like as we approach the equator?" This project involves visualizing weather data from over 500 cities, analyzing the relationship between weather variables and latitude, and using this information to plan future vacations.

### Results:
1. __WeatherPy:__ Create a Python script to visualize weather data for over 500 cities across varying distances from the equator. Use the citipy Python library, the OpenWeatherMap API, and problem-solving skills to build a representative model of weather conditions.
   - Generate random geographic coordinates and find the nearest city to each latitude and longitude combination.
   - Retrieve weather data using the OpenWeatherMap API.
   - Create scatter plots showcasing relationships between latitude and weather variables: Temperature, Humidity, Cloudiness, and Wind Speed.
   - Compute linear regression for each relationship and create scatter plots for Northern and Southern Hemispheres.
   - Analyze and describe the relationships observed in the plots.

2.__*VacationPy:__ Utilize weather data skills to plan future vacations using Jupyter notebooks, the geoViews Python library, and the Geoapify API.
   - Create a map displaying cities based on their coordinates and humidity.
   - Narrow down cities based on specific weather conditions such as temperature, wind speed, and cloudiness.
   - Create a DataFrame to store city, country, coordinates, and humidity.
   - Use the Geoapify API to find the nearest hotel within 10,000 meters of each city's coordinates.
   - Add hotel names and countries as additional information in hover messages on the map.