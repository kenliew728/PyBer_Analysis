# **PyBer Analysis - Ride Sharing Summary by City Type**
## **Analysis Overview**

The purpose of the report is to provide an analysis of how the total fare ride differs by city type, and what can be done to improve the disparity among city types, should the outcome of the study supports the disparity hypothesis. 

## **Results**

Based on the city and ride data, the following conclusions can be made in respective to city type:

1. ***Urban Area***
   - Urban area made up of 68.4% of the total rides, 80.9% of the total drivers and 62.7% of the total collected fares. However, it trailed both suburban and rural area in average fare per ride and per driver compares to suburban and rural area.
2. ***Suburban Area***
   - Suburban area made up of 26.3% of the total rides, 16.5% of the total drivers, and 30.5% of the total collected fares . Suburban area was in the middle of the pack in average fare per ride and driver. 
3. ***Rural Area***
   - Rural area made up of 5.3% of the total rides, 2.6% of the total drivers, and 6.8% of the total collected fares. However, the drivers were making more money since the average fare per ride and per driver was the highest among all city type.
#### *Table 1.1: Total rides/driver and average fare per ride/driver summary*
![Pyber challenge dataframe summary](https://user-images.githubusercontent.com/70525492/95369069-8a1cdd80-089c-11eb-9d34-1b41ad055807.png)

The merged data was group by date and type of city in respective to total fares and a line chart was ploitted. The study period was filtered from January 1st 2019 to April 29th 2019. The purpose of the study is to visualize if disparity exist in total collected fares per week by city type.  

Based on the line chart displayed below, the following conclusions can be made:

1. The disparity observed was in contrast with the average fare analysis. While the drivers in urban area made less money, they have consistently pulled in more fares per week compare to suburban and rural areas during the study period.   
2. The total fares by city type in the selected study period are as follow:
   - Urban: $37,065.78 (63.0%)
   - Suburban: $17,883.34 (30.4%)
   - Rural: $3,913.69 (6.6%)

#### *Fig 1.1: Total Fare by City Type in Weekly bucket
![PyBer_fare_summary](https://user-images.githubusercontent.com/70525492/95600528-e7896980-0a17-11eb-9b9c-4224b1fb64c4.png)


## **Summary**
Business recommendations for addressing disparities among the city types
1. **Alternate method of hailing ride share service in rural areas**
   - Smartphone is required in order to utilize ride hailing apps, which means cell tower reception will need to be reliable. However cellphone service in rural areas are usually spotty or non-existent. PyBer should attempt to provide different way of hailing ride like a call-center in order to increase ridership in rural areas
2. **Charging flat rates in suburban and rural areas based on mile radius**
   - Ride hailing service made better sense when you need to travel short distance such as those in the urban areas. 
   - Customers who hailed ride servie in rural areas, and in some cases, suburban areas, typically need to travel a longer distances, which made the fares expensive, and preventing more customer to use the service. 
   - Charging a flat rate may help improves ride hailing ridership. 
3. **Ride now pays later method in rural area**
   - Rural area may not be used to credit card or online payment method and their mode of payment could be cash or checks only.
   - PyBer can attempt to use a system that allows customers to pay in check or send a bill to the customer to allow them to pay at a later date.

