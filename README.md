# Project-no.-1
This includes files for project #1
## Repo Structure
The repository includes the following files
  -[Raw Data](AirQuality_Daily_StudentVersion.csv)
  -[Notebook](CIVE202.Spring2026.CollinMangnall.Project1.fileextension.ipynb)
The goal of this project is to analyze air quality data from February 2024 to March 2025. We are asked to find if the air quality is meeting National Ambient Air Quality Standards (NAAQS) and if “hot spots” of the air quality exist, and see if that has any health concerns. They have requested 4 key analyses: (1) 5 locations in Nebraska with the highest mean and median concentration, (2) Days the maximum occurs and where, (3) if humidity and temperature have a noticeable effect on air quality, (4) if there have been any Air Quality Index (AQI) health risks.
Project Tasks:
To achieve the project goals, these steps will be taken to finish the tasks.
Task 1: 5 locations in Nebraska with the highest mean and median concentration
With the data given, I will use the aggregate function to separate the sensor names by their mean and median concentrations for each type. With this, I can find the five highest and report their names and locations. These will track the air pollution in each of their scales and will show where that concentration is consistently greater than in the other places.
Task 2: Days on which the maximum occurs and where
For this task, it will be mostly the same process as task 1. We will use the group by and aggregate functions to be able to separate the values by sensor names. With the aggregate function, we will ask for the maximum in that area. This will then show the max and the sensor name, which is where it occurred.



Task 3: Humidity and temperature affect air quality
To see if humidity and temperature affect air quality, we need to separate those two quantities and look at the air pollution concentrations. Different ways to separate to get accurate data are low humidity, high humidity, and very high humidity, and for temperature freezing, cool, warm, and hot. Looking at each of these will give an accurate depiction of the effect that these two have on the air quality. 
Task 4: Any days with Air Quality Index (AQI) health risks
Within the data given, the air pollution concentration has numbers where it determines the air quality on that day. While the concentration increases, so does the air quality risk. Knowing this, we can separate the data by its max values to see the days that the risk was met and the causes that could’ve made this occur.

