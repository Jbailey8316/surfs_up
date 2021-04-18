# surfs_up
## Project Overview
The purpose of this analysis is to reasearch weather conditions on the island of Oahu using SQLlite, Python, SQLAlchemy, and Flask for data storage and retrieval.  The results of this analysis will be used for a business venture with W. Avy. There is the potential to open an ice cream and surf shop in this area if the weather conditons year round are favorable.

## Resources
* Data Source #1: hawaii.sqlite
* Software: Pyhton 3.9.2 64 bit, Jupyter Notebook 6.1.4, SQLite, Flask

## Results
Results of our analysis conclude the following:
* **Temperature averages for the month of June are around 75ºF**
* **Temperature averages for the month of December are around 71ºF**
* **Minimum temperatures range from 64ºF in June to 56ºF in December**

Using the provided weather data from the collection stations we were able to extract several key aspects including average temperatures, minimum temperatures, and maximum temperatures.  The lowest temperatures were 64ºF in June and 56ºF in December.  The highest temperatures were 85ºF in June and 83ºF in December with the average temperature being 75ºF in June and 71ºF in December.  Furthermore, we can conclude from the temperature's standard deviation of June (3.25) and December (3.75) that there is a very low variance of 0.5 within the averages.

### Fig 1.  June Data Statistics
![june_temp_stats](https://github.com/Jbailey8316/surfs_up/blob/main/Images/june_temp_stats.PNG)

### Fig 2. June Temperatures
![june_chart](https://github.com/Jbailey8316/surfs_up/blob/main/Images/june_temps.PNG)

### Fig 3. December Data Statistics
![dec_temp_stats](https://github.com/Jbailey8316/surfs_up/blob/main/Images/dec_temp_stats.PNG)

### Fig 4. December Temperatures
![dec_chart](https://github.com/Jbailey8316/surfs_up/blob/main/Images/dec_temps.PNG)

## Summary
Upon further investigation we can query the amount of rainfall for our selected months.  June had an average rainfail of 0.14 and 0.22 in December.  The highest amount of rainfall occured in December at 6.42. In conclusion, we can determine the weather on the island of Oahu is quite moderate with pleasant temperatures and a low rainfall averages for the months in question.  These factors indicate that a potential surf and ice cream shop would likely do well in this area.

### Fig 5. Rainfall For June
![june_rain_chart](https://github.com/Jbailey8316/surfs_up/blob/main/Images/june_rainfall.PNG)

### Fig 6. Rainfall Statistics for June
![june_rain](https://github.com/Jbailey8316/surfs_up/blob/main/Images/june_rain_stats.PNG)

### Fig. 7 Rainfall For December
![dec_rain_chart](https://github.com/Jbailey8316/surfs_up/blob/main/Images/dec_rainfall.PNG)

### Fig. 8 Rainfall Statistics For December
![dec_rain](https://github.com/Jbailey8316/surfs_up/blob/main/Images/dec_rain_stats.PNG)
