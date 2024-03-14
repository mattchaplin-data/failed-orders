# failed-orders
---
Insights from Failed Orders: An analysis of failed taxi orders for corporate Ground Transportation Management company Gett

## Objective
---
To investigate matching metrics for orders that did not complete successfully, meaning the customer didn't end up getting a car. 

## Data
---
Dataset covering a snapshot of taxi orders in Reading UK. Downloaded from [StrataScratch](https://platform.stratascratch.com/data-projects/insights-failed-orders) on Feb 25. 2024.

## Skills & Tools
---
- Data sourcing
- -Python: numpy, pandas, matplotlib
- Exploratory Data Analysis
- Data wrangling & subsetting
- Data visualization with Tableau
- Geographical visualization
- Dashboard building

## Analysis
---
- Performed EDA  in python to identify relationships of interest within the data
- Grouped orders and built up a distribution according to reasons for order failure
- Investigated the relationships of grouped orders to our of day, order ETA and Time to Cancellation
- Created an analytical dashboard on [Tableau](https://public.tableau.com/views/InsightsfromFailedTaxiOrders_17097075758860/InsightsfromFailedOrders?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) to communicate findings

## Insights
---
-There are significantly more cancellations in the city centre around the main transport links, shopping district and the university
-Overnight orders are far less likely to be cancelled once a driver had been assigned
-Despite a large number of orders overnight being cancelled before a driver is assigned, the overnight ETA of assigned orders remains below 400s
-Orders with a driver assigned take significantly longer to be cancelled
-Overnight customers with a driver assigned take longer to cancel than those during the day

  
