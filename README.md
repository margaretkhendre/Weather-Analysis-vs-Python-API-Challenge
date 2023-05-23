# Python API Challenge

### Background
You are challenged with the question, "What is the weather like as we approach the equator?"
We know it gets hotter, but let's prove it...

## Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

### Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the [citipy Python library](https://pypi.org/project/citipy/), the [OpenWeatherMap API](https://openweathermap.org/api), and your problem-solving skills to create a representative model of weather across cities.

**Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude**
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature

- Latitude vs. Humidity

- Latitude vs. Cloudiness

- Latitude vs. Wind Speed

**Requirement 2: Compute Linear Regression for Each Relationship**
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

<img width="599" alt="Screenshot 2023-05-23 at 3 48 22 PM" src="https://github.com/margaretkhendre/Weather-Analysis-vs-Python-API-Challenge/assets/121995835/138f918f-9503-4eab-9a3f-670ba7451e2a">

Create the following plots:

- Northern Hemisphere: Temperature vs. Latitude

- Southern Hemisphere: Temperature vs. Latitude

- Northern Hemisphere: Humidity vs. Latitude

- Southern Hemisphere: Humidity vs. Latitude

- Northern Hemisphere: Cloudiness vs. Latitude

- Southern Hemisphere: Cloudiness vs. Latitude

- Northern Hemisphere: Wind Speed vs. Latitude

- Southern Hemisphere: Wind Speed vs. Latitude

### Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

Use the VacationPy.ipynb starter code and complete the following steps:

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

<img width="699" alt="Screenshot 2023-05-23 at 3 44 59 PM" src="https://github.com/margaretkhendre/Weather-Analysis-vs-Python-API-Challenge/assets/121995835/9a396c6d-ca5c-4052-9f54-1b6ce24d8adc">


2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

- A max temperature lower than 27 degrees but higher than 21

- Wind speed less than 4.5 m/s

- Zero cloudiness

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

<img width="691" alt="Screenshot 2023-05-23 at 3 59 35 PM" src="https://github.com/margaretkhendre/Weather-Analysis-vs-Python-API-Challenge/assets/121995835/87236c05-4de9-42af-93fa-fa353736ea69">


