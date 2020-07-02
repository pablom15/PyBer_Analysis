# PyBer_Analysis Report

## Background and Results

### Purpose
Pyber, a ride sharing app company, has assigned me the task of analyzing a large dataset from their ride share data. This data includes the type of city, number of riders, number of drivers, and ride fare cost. Results from this data are to drawn by utilizing matplotlib to plot the data and by creating pandas data frames to set up the data for plotting.

### Technical Analysis
The summary data table and plot for this challenge are shown below. The table shows rider, driver, and fare data based on city type. The multiple-line graph shows fare data for each week by city type.

### Results

![Pandas_Summary_Table_by_City_Type](Analysis/Challenge_DF.png)

![Weekly_Total_Fare_by_City_Type](Analysis/Challenge.png)

### Summary
The pandas summary data table shows that the urban cities result in the greatest amount of Total Rides, Total Drivers, and Total Fares with suburban and rural cities having the second and third highest, respectively. When analyzing the average fare price per ride and average fare per driver, the rural cities have the highest average price in both categories with suburban and urban cities having the second and third highest, respectively. 

The line chart shows the results for each city types total fares over a weekly basis from January through April of 2019. From this plot, we conclude that urban cities have the highest amount of total fares with suburban and rural having the second and third highest, respectively. There is also a significant increase at the end of February and middle of March for all of the city types.

Ultimately the urban cities generate the most money in total fares due to their large amount of riders but their fare price is lower compared to other cities. Their high number of drivers results in a significantly low average fare per driver when compared to other city types. Fare prices in rural cities are higher and their low number of riders and drivers. 

## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

* Programming
    - The challenges encountered during the programming of this analysis were working with a datetime index and creating a pivot table. This was only a challenge because it was the first time to filter through and analyze data through this method in Pandas.

* Data analysis
    - There were no challenges in the data analysis but confirming the data types of the data set and making sure the index was set to a date time data type are very important in this analysis.

* Graphing, etc
    - There were no challenges when plotting but making sure to increase the figure size is important to read the plot easily and accurately.

### Technical Analyses Used

## Recommendations and Next Steps
I would recommend to increase the fare price for urban cities and reduce the number of drivers by using performance reviews. I would also recommend to increase fare prices during 'hot weeks' such as the end of February and middle of March (this is most likely Spring Break week). Decreasing the fare price for rural cities may result in more drivers and the increase of urban fares will help with that offset while still bringing in more revenue in fares.

### Recommendations for Future Analysis

### Additional Analysis 1

* Description of Approach
    - An analysis could be done to see if certain times of the day are busier and what the average fare price is during those times. Fare prices can be increased during busy hours of the days.

* Technical Steps
    - This analysis would be similar to the weekly data but the data would be binned by time in 2-4 hour increments instead of weeks. Plotting a bar chart of total rides for each city type at each time bin would help see what one days activity looks like and be able to adjust fare price based on time. 

### Additional Analysis 2

* Description of Approach
    - Another analysis that could be performed is to analyze each city type separately in order to determine which cities have high and low performance.

* Technical Steps
    - A data frame for each city type would be the first step in this analysis. From there, fare and ride data can be analyzed in order to determine which cities are performing high and which cities are not and if fare price or driver count can be adjusted in any way. A pie chart of percentage of total fares for each city in a certain city type would be an example of one plot for this analysis.