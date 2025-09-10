# OPTIMIZING PUPLIC TRANSPORT
## Turning messy transit data into clear insights to improve efficiency, passenger experience, and decision-making in public transport.
![image alt](https://github.com/yvonnemetet-netizen/My-Image-folder-/blob/main/Multple%20transport.jpg?raw=true)
## Introduction
This project aims to support MetroMove Transit Solutions- a public transportation service provider operating in multiple cities.
who manage and analyze thousands of daily trips taken via buses, trains, ferries, and trams.
The Company's mission is to provide efficient, affordable, and timely public transportation services while leveraging data to improve passenger experience and optimize operations.


## Problem Statement
1. MetroMove has collected a large volume of data which is messy, inconsistent, and incomplete.
2. The company has no insights on trip performance, passenger behavior, and fare patterns.
3. The new data-driven initiative is to:
  - Clean, explore, and summarize trip records,
  - Identify inefficiencies and key patterns.
  - Drive operational improvements


## Aim of The Project 
1. Understanding passenger usage patterns.
2. Evaluating the performance of different transport modes.
3. Analyzing how trip characteristics impact customer experience.


## Methodology
1. Library Setup-Imported essential Python libraries for data cleaning,
 exploration, and visualization in Jupyter Notebook.
2. Data Ingestion- Loaded the CSV file containing transport trip data.
3. Data Cleaning:
   - Resolved inconsistencies across key columns.
   - Handled missing values to ensure data integrity.
4. Feature Engineering:
   - Extracted month and year from trip_date.
   - Created new variables including:
   - Route (departure + arrival station)
   - Departure_hour (from departure time)
5.  Exploratory Analysis- Performed descriptive and visual analysis to identify
 patterns, trends, and anomalies.


## Libraries Used 
1. Pandas – for data cleaning and manipulation
2. Numpy – for numerical computations and efficient data handling
3. Matplotlib – for static data visualization and plots
4. Seaborn – for advanced, visually appealing statistical graphics


## Exploratory Data Analysis
## Bar Chart 
- This chart compares the total passenger counts, trip durations, and fare amounts across the different modes of transport. Buses dominate in all categories, carrying the largest share of passengers, trips, and fares. At the other end of the scale, trams record the lowest totals, reflecting their smaller role in the system.

- Looking at the averages, trip durations are fairly consistent across modes, with bus trips running slightly longer. Trams stand out with the highest average passenger count per trip, followed by ferries and buses, while trains carry slightly fewer passengers per trip. Average fare amounts are also quite similar, with trains priced marginally higher and ferries a bit lower.


- Overall, while the scale of operations varies significantly between modes, the per-trip experience, measured in trip duration, passenger count, and amount of fare, remains relatively balanced across the system. The key contrasts lie in the overall scale of operations, not in the characteristics of each individual trip.


![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Sum_vs_Avg_fare_pass_trip_by_transport.png?raw=true)


- Sunday records the highest total fares and passenger counts, making it the system’s peak travel day. In contrast, Thursday shows the lowest totals, reflecting weaker overall demand. Saturday and Tuesday stand out with relatively high passenger counts but lower fare totals, suggesting a larger number of shorter or lower-priced trips.


- When looking at averages, Thursday has a moderate passenger count but the highest fare per trip, which could point to longer journeys, premium pricing, or fewer discounts. Saturday records the highest average passenger count but comparatively low fares, consistent with high-volume, short-distance trips. Friday shows both low average passenger counts and fares, likely reflecting reduced commuting activity as the week winds down.


![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Passenger_Fare_Totals_vs_Averages.png?raw=true)


- The route from North Station to the Airport records the highest total passenger count and the longest cumulative trip duration, making it both the busiest and most time-consuming connection in the network. In contrast, the Central–Airport route generates the highest total fare revenue, suggesting it operates as a premium or high-value service despite not carrying the largest passenger volume.
  
![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Fare_trip_Pass_Route.png?raw=true)


## Scatter Plot
- The regression lines are almost flat suggesting fare pricing is relatively stable regardless of passenger count that is fares don’t really drop or increase based on how full the trip is.
  
![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Passenger_vs_Fare_by_Mode.png?raw=true)


- Across all transport modes, fare amount does not strongly increase with trip duration. The regression lines are almost flat, with slight declines in some modes, meaning longer trips don’t always mean higher fares.
  
![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Duration_vs_Fare_by_Mode.png?raw=true)


## Line Plot 
- Passenger traffic follows a predictable commute rhythm (morning surge, mid-day dip, evening pickup), but fare patterns hint at a mix of trip types. Peak fares sometimes appear in off-peak hours, showing that revenue doesn’t always depend on massive passenger numbers. Trip distance and type matter just as much.


![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/comp_Pass_fare_hour.png?raw=true)


## Pie Chart
- Central Station handles the highest number of departures, making it the busiest origin point in the network. In contrast, South Point records the lowest departures, highlighting it as the least active starting station. On the arrival side, the Airport receives the highest passenger traffic, positioning it as the most frequent destination. North Station, however, records the fewest arrivals, marking it as the least visited endpoint.


![image alt](https://github.com/yvonnemetet-netizen/Optimizing-Public-Transport-/blob/main/Passenger_Traffic_PieCharts.png?raw=true)




## Recommendations
The analysis highlights both operational strengths and areas for improvement. To act on these insights, MetroMove could:


- Adjust service allocation: Add more capacity on Sundays, the busiest travel day, and scale back or incentivize demand on quieter Thursdays.


- Refine fare strategy: Review Thursday’s high average fares for fairness, and optimize Saturday pricing to capture more revenue from high-volume, short-distance trips.


- Optimize modes: Strengthen tram services where loads are consistently high, while improving bus efficiency through route adjustments or priority lanes.


- Balance peak vs. off-peak: Introduce promotions or differentiated services to smooth passenger demand and strengthen off-peak revenue.
  
- Prioritize key routes: Increase scheduling efficiency and capacity on the North Station–Airport route to handle heavy traffic and long durations.


- Leverage premium routes: Capitalize on the Central–Airport connection by maintaining quality service and exploring premium pricing or value-added options.


## Thank You 

