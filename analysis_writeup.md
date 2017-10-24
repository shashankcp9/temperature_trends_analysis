# Trend Analysis for Miami v/s Global Temperature Data

## 1.)  Extracting the data

A.) Query to extract global data:

SELECT *
FROM global_data;
B.) Query to extract city data:

SELECT *
FROM city_data
WHERE city = 'Miami';

After extracting the data download csv and analysis was performed in google sheets.

## 2.) Line Graph: [Link to Graph](https://docs.google.com/spreadsheets/d/1tqgr-6lxp3mqp0K7AjEiH9xJN8GtRf_xA3rN_3OA1mI/edit?usp=sharing)

* The moving average in the above line graph was calculated for every 10 years.
* The moving average was calculated individually for the city and global data and then were combined together corresponding to their years.
* After this, the data was selected from the new sheet and a line graph was inserted to observe and compare the changes in temperature between the two groups.


## 3.) Observations:
1. Miami is very hot compared to the global temperature.

2. Although the temperatures are vastly different in numbers, the difference between the two temperatures are largely consistent when observing the trends of the graph. 
	
3. If you observe the temperature from 1807 to 1818, you’ll see the similarities in the trends between the two temperatures. The rise and fall of both are quite similar and this pattern continues along till the year 1950, where you will find a slight increase and then decline in the city temperature while the global temperature remains consistent.
	
4. The world is getting hotter when we observe the overall trend. If we consider in intervals of one hundred years, we can see how quickly the temperature has escalated within the last hundred years: 1801-1900 temperature decreased by -0.219 and in 1901-2000 it increased by 0.897.


