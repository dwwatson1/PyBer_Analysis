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

Unsurprisingly, PyBer has the most demand for riders and drivers in urban areas while rural had the least demand. There were a total of 1,625 rides and 2,405 drivers, which generated the highest number in total fares: **$39,854.38**. Suburban areas have the second-most demand for PyBer riders and drivers with 625 riders, 490 drivers, and **$19,356.33** in total fares, followed by rural areas with 125 rides, 78 drivers, and **$4,327.93** in total fares. While urban areas were the most popular for PyBer in terms of total riders and drivers, the city type yielded the lowest average fare per ride with **$24.53** and **$16.57** average fare per driver. Suburban areas had the second-highest average fare per ride at **$30.97**, and average fare per driver at **$39.50**. Rural areas had the highest average fare per ride, **$34.62**, and average fare per driver, **$55.49**.

Even though urban areas had the lowest average fare per ride and per driver, the high demand for drivers and rides generated 9x more in total fares than in rural areas and twice as much than in suburban areas. The scatter plot below shows the frequency of rides by average fare. Please note that the circle size correlates with driver count per city.

![Fig.1](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/Fig1.png)

The average fare for urban rides never crossed $30 but as shown by the number of red plots and the size of the plots, there was a high demand for riders and drivers. Because of this demand, total fares for urban areas account for nearly **$40,000** and **nearly 63%** of all PyBer fares.

![Fig.5](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/Fig5.png)

Looking at a four-month snapshot from January - April 2019, we can see the same pattern as mentioned above. Urban areas consistently yielded the highest in total fares each week as it never dipped below **$1,500 a week**. Suburban areas never crossed the $1,500 per week in total fares but were consistently above the **$500 mark**. Rural areas struggled to generate much in total fares as it only crossed the **$500 per week** threshold only once and dipping below $100 twice. Weekly total fares by city type in this timeframe are shown in the line chart below.

![PyBer_fare_summary](https://github.com/dwwatson1/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary of the Analysis

### Business Recommendations

-  Urban areas generate the most in total fares and should be the main focus for PyBer's expansion in the next **5 years**. PyBer would benefit from digital advertising in new cities to gain new riders and drivers. The emphasis here is getting as many riders and drivers as possible because their average fares are much lower than in suburban and rural areas.
-  Suburban and rural areas shouldn't be overlooked. Looking at the weekly total fares in the snapshot above, the numbers are fairly consistent, even though they're lower than urban areas. They both account for **33% of total fares**, which is substantial. PyBer could benefit from light digital marketing in the suburban areas outside of the expansion urban areas.
-  There is specific untapped potential in rural areas. As broadband, 5G cell service, and credit card usage expand in rural areas, it could be lucrative for PyBer because of the higher average fare per driver and ride. Expansion in rural areas will take longer and should be a part of PyBer's **10-15 year plan**. No immediate marketing is necessary, but we need to keep monitoring app downloads and rider/driver usage in rural areas. One longer-term plan would be to pay rural drivers more than suburban and urban drivers to provide incentives and provide access for riders. This has been a problem for Lyft and Uber as the pay for rural drivers isn't lucrative enough to keep driving while making a living wage.

### Important Things to Note
  
It's important to note that the length (time and miles driven) of PyBer rides is a key missing data point. This could provide context as to why the average fares per ride and driver are much higher than any other city type and why riders and drivers are so few. Likely, PyBer rides in rural areas take longer given that people who live in these rural areas need to travel longer distances. Upon further research into other ride-hailing apps like Uber and Lyft, there is an [urban-rural divide](https://www.vox.com/the-goods/2019/1/11/18179036/uber-lyft-rural-areas-subscription-model) in terms of usage. 

This divide is compounded by the lack of reliable broadband internet and credit card usage, as suggested in the research mentioned in the article. This makes it harder for people in rural communities to use an app, which requires cell service or WiFi. Car ownership may be higher in rural areas because people need to travel longer distances and parking is easier to find, unlike in urban areas. These reasons could also explain why the demand for PyBer rides in rural areas is so low. However, this isn't always the case and shouldn't be overlooked as a market for potential expansion. 
