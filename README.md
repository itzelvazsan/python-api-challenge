# python-api-challenge

By: Itzel Vázquez Sánchez

## Project Description :page_facing_up:

This project is part of the Data Analysis and Visualization Bootcamp from Tecnológico de Monterrey. In this assignment, the task was to manipulate Pandas DataFrames to practice Python requests, APIs, and JSON traversals in order to answer this question: "What is the weather like as we approach the equator?".

🤓 This Project is the result of the learning lessons of Module 6: Python APIs from the Data Analysis and Visualization Bootcamp 2024. The main goal is to use the acquired habilities and knowledge in a real case. 

## Table of contents :point_right:

On the repository you'll find:

| Item  |   File Type          |         File Name              |           Description                                                            |
| ----- | -------------------  | ------------------------------ | -------------------------------------------------------------------------------  |
|   1   | Jupyter Notebook     |  WeatherPy                     |  Jupyter notebook with answers to first deliverable                              |
|   2   | Jupyter Notebook     |   VacationPy                   | Jupyter notebook with answers to second deliverable                              | 
|   3   |   folder             |   output_data                  | Folder that contains: cities.csv; Fig1.png; Fig2.png; Fig3.png; Fig4.png         |

## How to Use the Project

### WeatherPy
The first deliverable should contain a series of plots and linear regressions of the following relationships:

* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

It includes an explanation of the linear regressions after the plots.

![image](https://github.com/user-attachments/assets/38539539-3b7e-4ef2-abaa-3a1aee3f3409)

### VacationPy
The second deliverable should contain:

* Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
![image](https://github.com/user-attachments/assets/b93dbcc6-c53b-40ba-b2c8-ec9cbf4f104c)
* Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
  - A max temperature lower than 27 degrees but higher than 21
  - Wind speed less than 4.5 m/s
  - Zero cloudiness
* Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
* For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
* Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
![image](https://github.com/user-attachments/assets/c647b862-ed19-47f7-b61b-b652c2addc12)


## Credits :scroll:
The code of this project origins from: starter code provided by the Team of the Data Analysis and Visualization Bootcamp, the solved exercises worked in the Zoom Lessons, [Stackoverflow](https://stackoverflow.com/), [hvPlot documentation](hvPlot/), [pandas documentation](https://pandas.pydata.org/docs/index.html), [Geoapify API documentation](https://apidocs.geoapify.com/docs/places/#categories), [matplotlib documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html), [python documentation](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) and Microsoft Copilot.

