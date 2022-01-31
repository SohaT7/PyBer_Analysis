# The PyBer Ride-Sharing Data Analysis

## Overview of the Analysis
This project analyzes and visualizes ride-sharing data, using Python, Pandas, and Matplotlib, in order to explore and visually represent the relationship between the type of city and drivers and riders, as well as the relationship between percentage of total fares, drivers and riders, by the type of city. The purpose of the project is to improve accessibility while determining the affordability patterns for the ride-sharing services provided by PyBer in under-served neighbourhoods especially. The purpose of the new analysis [PyBer_Challenge](https://github.com/SohaT7/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb) is to determine how the total weekly fares differ by city type in order to come up with more effective strategies when it comes to addressing those disparities. 

## Results
![PyBer Summary DataFrame](https://github.com/SohaT7/PyBer_Analysis/blob/main/analysis/PyBer%20Summary%20DataFrame.png)

The summary dataframe we created showcases data for total rides, total drivers, total fares, average fare per ride, and average fare per driver by city type.
Rural cities have the lowest number of total rides at 125 which is 5 times lower than that for suburban cities (at 625) and 13 times lower than urban cities (at 1,625). Rural cities also have the lowest number of total drivers at 78, which is almost 6 times lower than that of suburban cities (at 490) and about 31 times lower than that of urban cities (at 2,405). Rural cities generate the lowest total fares at $4,327.93, which is 4.5 times lower than suburban's (at $19,356.33) and 92 times lower than urban's (at $39,854.38). 

Average Fare per Ride was calculated by dividing Total Fares by Total Rides for each city type. Average Fare per Ride is highest for rural cities at $34.62, followed by suburban's at $30.97, and urban's at $24.53. Average Fare per Driver was calculated by dividing Total Fares by Total Drivers for each city type. Average Fare per Driver is highest for rural cities at $55.49, followed by suburban's at $39.50, and urban's at $16.57. In effect, we can say, the average fare is pricey in rural cities than it is in urban cities (or suburban cities). 

![Multiple Line Chart](https://github.com/SohaT7/PyBer_Analysis/blob/main/analysis/Fig_TotalFareByCityType_Chart.png)

The multiple line chart we created showcases the total fares made each week for each city type. The total weekly fares are higher for urban cities (higher than roughly $1,600), followed by suburban's (roughly between $700 and $1,500), and lastly by rural's (roughly between $0 and $500). The highest total weekly fare for urban cities at $2,500 was at the end of the third week of February 2019 and the end of the first week of March 2019. The total weekly fare for urban cities starts to increase from January (about $1,650) all the way through to end of third week of February wher eit peaks ($2,500), followed by a momentary dip start of March (at about $2,250) and a peak again a the end of the first week of March (at $2,500). Thereafter, the total weekly fares follow some dips and peaks (though none as high as $2,500). The total weekly fares for the suburban cities start to increase from January (about $750)with a slught dip in February before it hits its peak in the third week of February at $1,500. It decreases thereafter, until it rises a little again around third week of March before dipping again into April. The rural weekly fares have very little variation in their range (about $500 only, as about to roughly $800 to $900 for the suburban and urban). The lowest weekly fare for rural cities is in first week of January 2019 at around $50 to $100, whereas the highest is around the start of April at $500.

## Summary
The following are some recommendations in order to address the disparities in the ride-sharing data from the three city types:
- The Average Fare per Ride in rural cities can be lowered when more rides are being booked and used. Total rides can be increased hiring more drivers (or better marketing, etc). Hiring more drivers will also lower the Average Fare per Driver in rural cities. 
- The Total Fares (and Total Rides) in the rural (and suburban) cities can be increased by hiring more drivers (for that might be a limiting factor in why more people are unable to take rides in these cities).
- The Total Drivers in urban cities (2,405) seem to exceed the Total Rides in urban cities (1,625), which points to how there might be an excess of drivers, and the reason why they are not getting any (or as many) rides is because no one needs more rides. This aspect needs to be looked at in depth to cpature the ground reality some more.
