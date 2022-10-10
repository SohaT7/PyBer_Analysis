# The PyBer Ride-Sharing Analysis
## Table of Contents
- [Overview of the Analysis](#overview-of-the-analysis)
    - [Purpose](#purpose)
    - [About the Dataset](#about-the-dataset)
    - [Tools Used](#tools-used)
    - [Description](#description)
- [Results](#results)
- [Summary](#summary)
- [Contact Information](#contact-information)

## Overview of the Analysis
### Purpose:
The purpose of the analysis is to determine how the total weekly fares differ by city type in order to come up with more effective strategies when it comes to addressing those disparities. 

### About the Dataset:
The dataset includes the following CSV files:
 - [City Data](https://github.com/SohaT7/PyBer_Analysis/blob/main/Resources/city_data.csv) - 120 records containing the fields: City, Driver Count, and Type
 - [Ride Data](https://github.com/SohaT7/PyBer_Analysis/blob/main/Resources/ride_data.csv) - 2375 records containing the fields: City, Date, Fare, Ride ID

### Tools Used:
 - Python (Pandas and Matplotlib libraries)

### Description:
A summary DataFrame containing ride-sharing data by city type, is created. This is done by first calculating the total number of rides, drivers, and fares for each city type, followed by average fare per ride and average fare per driver for each city type. This is then added to a new DataFrame, and the columns formatted. Next, a multiple-line graph is created, which visualizes the total weekly fares for each city type. 

## Results
![PyBer Summary DataFrame](https://github.com/SohaT7/PyBer_Analysis/blob/main/analysis/PyBer%20Summary%20DataFrame.png)

The summary dataframe we created showcases data for total rides, total drivers, total fares, average fare per ride, and average fare per driver by city type.
Rural cities have the lowest number of total rides at 125, which is 5 times lower than that for suburban cities (at 625) and 13 times lower than urban cities (at 1,625). Rural cities also have the lowest number of total drivers at 78, which is almost 6 times lower than that of suburban cities (at 490) and about 31 times lower than that of urban cities (at 2,405). Rural cities generate the lowest total fares at $4,327.93, which is 4.5 times lower than suburban's (at $19,356.33) and 92 times lower than urban's (at $39,854.38). 

Average Fare per Ride was calculated by dividing Total Fares by Total Rides for each city type. Average Fare per Ride is highest for rural cities at $34.62, followed by suburban's at $30.97, and urban's at $24.53. Average Fare per Driver was calculated by dividing Total Fares by Total Drivers for each city type. Average Fare per Driver is highest for rural cities at $55.49, followed by suburban's at $39.50, and urban's at $16.57. In effect, we can say, the average fare is pricey in rural cities than it is in urban cities (or suburban cities). 

![Multiple Line Chart](https://github.com/SohaT7/PyBer_Analysis/blob/main/analysis/Fig_TotalFareByCityType_Chart.png)

The multiple line chart we created showcases the total fares made each week for each city type. The total weekly fares are higher for urban cities (higher than roughly $1,600), followed by suburban's (roughly between $700 and $1,500), and lastly by rural's (roughly between $0 and $500). The highest total weekly fare for urban cities at $2,500 was at the end of the third week of February 2019 and the end of the first week of March 2019. The total weekly fare for urban cities starts to increase from January (about $1,650) all the way through to end of third week of February, where it peaks ($2,500), followed by a momentary dip start of March (at about $2,250), and a peak again a the end of the first week of March (at $2,500). Thereafter, the total weekly fares follow some dips and peaks (though none as high as $2,500). The total weekly fares for the suburban cities start to increase from January (about $750) with a slight dip in February, before it hits its peak in the third week of February at $1,500. It decreases thereafter, until it rises a little again around third week of March before dipping again into April. The rural weekly fares have very little variation in their range (about $500 only, as opposed to roughly $800 to $900 for the suburban and urban). The lowest weekly fare for rural cities is in first week of January 2019 at around $50 to $100, whereas the highest is around the start of April at $500.

## Summary
The following are some recommendations in order to address the disparities in the ride-sharing data from the three city types:
- The Average Fare per Ride in rural cities can be lowered when more rides are being booked and used. Total rides can be increased by hiring more drivers (or better marketing, etc). Hiring more drivers will also lower the Average Fare per Driver in rural cities. 
- The Total Fares (and Total Rides) in the rural (and suburban) cities can be increased by hiring more drivers (for that might be a limiting factor in why more people are unable to take rides in these cities).
- The Total Drivers in urban cities (2,405) seem to exceed the Total Rides in urban cities (1,625), which points to how there might be an excess of drivers, and the reason why they are not getting any (or as many) rides is because no one needs more rides. This aspect needs to be looked at in depth to capture the ground reality some more.

## Contact Information
Email: st.sohatariq@gmail.com
