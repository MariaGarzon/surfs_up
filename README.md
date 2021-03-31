# Weather Analysis for Oahu Surf & Ice Cream Shop 

## Overview 

The purpose of this project is to perform statistical analysis on temperature data for the months of June and December in Oahu to determine if a surf and ice cream shop business is sustainable year-round. 

## Resources

- Data Souce:
- Tools: SQLite, SQLAlchemy, Flask 


## Results

The data extracted for each month gave us the following information: 

### December

![December Histogram](https://github.com/MariaGarzon/surfs_up/blob/92da2e597a9deb49cc47d60ed1696b8607801f2b/images/Dec_temp_hist.png)

1) The average temperature is 71.04 °F
2) The minimum temperature is 56 °F
3) The maximum temperature is 83 °F
4) 
### June

![June Histogram](https://github.com/MariaGarzon/surfs_up/blob/92da2e597a9deb49cc47d60ed1696b8607801f2b/images/june_temp_hist.png)  

1) The average temperature is 74.94 °F
2) The minimum temperature is 64.00 °F
3) The maximum temperature is 85.00 °F

### Main Takeaways

  •	The is an unequal sample size, as June has a total of 1700 observations and December has 1517. This amounts to a difference of 183    
    data points. 
    
  •	The temperature mean differs by 3.9 degrees, with June having an average of 74.9 °F and December 71.0 °F. 
  
  •	There June data is slightly skewed to the left, whereas the December data has a symmetrical distribution. 

# Summary

Based on the summary statistics, June's lowest temperature is 64 °F, but only 25% of the month falls below 73 °F. In contrast December can go as low as 56 °F, with 25% of the month being at or below 69 °F. Additionally, June is on average warmer than 50% of the month of December. 

A limitation of this data is it is not indicated the time of day that temperatures were taken or if it was an average of each day. 

For further analysis, it would be helpful to look at the precipitation levels of each month. 
