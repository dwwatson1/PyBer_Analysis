# PyBer Rideshare Analysis

## Overview of the Analysis

The purpose of this analysis was to analyze and visualize ride-sharing data from PyBer, a python-based ride-sharing app company, using the power of Python, Pandas, and Matplotlib. The CEO of PyBer, V. Isualize, tasked us with creating a report to show how the company's ride-sharing data differs by city type. These differences will help the CEO and other key decision-makers at PyBer understand which city types will yield the most profit for a growing company.

## Results of the Analysis

### Analysis Resources
* Data Sources: [PyBer_ride_data](https://github.com/dwwatson1/PyBer_Analysis/blob/main/Resources/PyBer_ride_data.csv), [city_data](https://github.com/dwwatson1/PyBer_Analysis/blob/main/Resources/city_data.csv), and [ride_data](https://github.com/dwwatson1/PyBer_Analysis/blob/main/Resources/ride_data.csv)
* Software: Jupyter Notebook 6.1.4 
* Notebooks: [PyBer](https://github.com/dwwatson1/PyBer_Analysis/blob/main/PyBer.ipynb) & [PyBer_Challenge](https://github.com/dwwatson1/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
 
### Overview of Results 

To understand the differences in PyBer rides in urban, suburban, and rural areas, we needed to create a summary dataframe to quantify the total rides, total drivers, total fares, average fare per ride, and average per driver. Using the analysis resources (above), we created the dataframe below to measure each of these metrics by city type. 

![PyBer_Overview](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/PyBer_Overview.PNG)

Unsurprisingly, PyBer has the most demand for riders and drivers in urban areas while rural had the least demand. There were a total of 1,625 rides and 2,405 drivers, which generated the highest number in total fares: $39,854.38. Suburban areas have the second-most demand for PyBer riders and drivers with 625 riders, 490 drivers, and $19,356.33 in total fares, followed by rural areas with 125 rides, 78 drivers, and $4,327.93 in total fares. While urban areas were the most popular for PyBer in terms of total rides and drivers, the city type yielded the lowest average fare per ride with $24.53 and $16.57 average fare per driver. Rural areas had the highest average fare per ride, $34.62 and average fare per driver, $55.49.

Even though urban areas had the lowest average fare per ride and per driver, the high demand for drivers and rides generated 9x more in total fares than in rural areas and twice as much than in suburban aras. The scatter plot below shows the frequency of rides by average fare. Please note that the circle size correlates with driver count per city.

![Fig.1](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/Fig1.png)

The average fare for urban rides never crossed $30 but as shown by the number of red plots and the size of the plots, there was a high demand for rides and drivers. Because of this demand, total fares for urban areas account for nearly $40,000 total and nearly 63% of all PyBer fares.

![Fig.5](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/Fig5.png)

Looking at a four month snapshot from January - April 2019, we can see the same pattern as mentioned above. Urban areas consistently yielded the highest in total fares each week as it never dipped below $1,500 a week. Suburban areas never crossed the $1,500 per week in total fares but was consistently above the $500 mark. Rural areas struggled to generate much in total fares as it only cross the $500 per week threshold only once and dipping below $100 twice.

![PyBer_fare_summary]https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png

## Summary of the Analysis

### Overview

### Important Things to Note
  
