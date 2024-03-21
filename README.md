# Python API Challenge

**Instructions:**
This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site, and your problem-solving skills to create a representative model of weather across cities. 

**Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude**

To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

**Requirement 2: Compute Linear Regression for Each Relationship**

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots. Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values. You should create the following plots:

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.


## Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter Notebook, the geoViews Python library, and the Geoapify API. Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, complete the following steps:

1. Create a map that displays a point for every city in the city_data_df DataFrame, as shown in the following image. The size of the point should be the humidity in each city.

2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

  - A max temperature lower than 27 degrees but higher than 21
  - Wind speed less than 4.5 m/s
  - Zero cloudiness

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5. Add the hotel name and the country as additional information.



## References:

Boston University School of Public Health (2021). The Correlation Coefficient (r). Retrieved from https://sphweb.bumc.bu.edu/otlt/MPH-Modules/PH717-QuantCore/PH717-Module9-Correlation-Regression/PH717-Module9-Correlation-Regression4.html

Geekforgeeks.org (n.d.). Change the order of a Pandas DataFrame columns in Python. Retrieved from https://www.geeksforgeeks.org/change-the-order-of-a-pandas-dataframe-columns-in-python/

Saturn Cloud (2024). How to Properly Copy a Pandas DataFrame into Another Variable: A Guide. Retrieved from https://saturncloud.io/blog/how-to-properly-copy-a-pandas-dataframe-into-another-variable-a-comprehensive-guide/#:~:text=To%20create%20a%20true%20copy,is%20known%20as%20deep%20copying.
