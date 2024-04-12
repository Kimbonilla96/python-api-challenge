Python API Challenge

Part 1: WeatherPy

  In this task, I was assigned to write a Python script to visually depict the weather patterns of more than 500 cities situated at various distances from the equator. Leveraging the citipy Python library, the OpenWeatherMap API, and your adept problem-solving abilities, you'll construct a comprehensive model illustrating weather conditions across these diverse locales. To facilitate your endeavor, you'll utilize the WeatherPy.ipynb Jupyter notebook included in the provided starter code ZIP file. Within this notebook, you'll find guidance on harnessing your Python coding prowess to tackle the specified requirements. Additionally, foundational code for generating random geographic coordinates and determining the nearest city based on latitude and longitude pairs is already furnished, streamlining your initial steps.
  Requirement 1: Generate Plots Demonstrating the Correlation Between Weather Parameters and Latitude
To meet this initial requirement, you'll employ the OpenWeatherMap API to gather weather information for the cities enumerated in the starter code. Subsequently, you'll craft a sequence of scatter plots to illustrate the following associations:
            Latitude vs. Temperature
            Latitude vs. Humidity
            Latitude vs. Cloudiness
            Latitude vs. Wind Speed

Requirement 2: Conduct Linear Regression Analysis for Each Association

  In accordance with the second requiement, I will conduct linear regression analyses for each relationship. Segment the plots into the Northern Hemisphere (latitude greater than or equal to 0 degrees) and the Southern Hemisphere (latitude less than 0 degrees). It may prove beneficial to establish a function to facilitate the creation of linear regression plots. Following this, generate a sequence of scatter plots. Ensure the inclusion of the linear regression line, the formula of the model, and the corresponding r values, as exemplified in the provided image.

  I was tasked with crafting the following sets of plots:
      Northern Hemisphere: Temperature vs. Latitude 
      Southern Hemisphere: Temperature vs. Latitude 
      Northern Hemisphere: Humidity vs. Latitude 
      Southern Hemisphere: Humidity vs. Latitude 
      Northern Hemisphere: Cloudiness vs. Latitude 
      Southern Hemisphere: Cloudiness vs. Latitude 
      Northern Hemisphere: Wind Speed vs. Latitude 
      Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy

  In this segment, I will leverage my expertise in weather data to strategize upcoming vacations. Alongside, you'll utilize Jupyter notebooks, the GeoViews Python library, and the Geoapify API. To streamline your initiation, essential code for importing requisite libraries and loading the CSV file containing weather and coordinate data for each city, as generated in Part 1, is provided. The primary objectives encompass harnessing the Geoapify API and the GeoViews Python library, alongside deploying my Python proficiency to craft map visualizations. To excel in this section of the assignment, access the VacationPy.ipynb starter code and accomplish the following tasks:

  Forge a map exhibiting a point representation for every city within the city_data_df DataFrame, mirroring the depiction depicted in the ensuing image. The magnitude of each point should correspond to the humidity level within the respective city.

  Refine the city_data_df DataFrame to pinpoint your desired weather conditions. For instance:
              Maximum temperature between 21 and 27 degrees Celsius
              Wind speed below 4.5 m/s
              Cloudiness at zero (NOTE: Feel free to adjust these criteria as needed, but ensure they remain within reasonable limits to manage the number of rows returned by API requests.)

Establish a fresh DataFrame named hotel_df to house pertinent details such as city, country, coordinates, and humidity.
Utilize the Geoapify API to identify the first hotel situated within a 10,000-meter radius of each city's coordinates.
Enhance the map visualization by incorporating the hotel name and country as supplementary information in the hover message for each city, emulating the format showcased in the provided image.
