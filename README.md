# WasteManagmentDWHAndAnalytics
This project is the final project of IBN course "Getting started with Data Warehousing and BI Analytics"
In This repository contains the code and documentation for the Solid Waste Management Data Warehouse project.
The project aims to create a data warehouse that will enable the company to generate various reports related to waste collection and recycling operations across major cities in Brazil.

1st Stage: Dwesigning our DWH:
a- MyDimDate: Design the dimension table for date-related data.
![1-DimDate](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/279d1d08-e74c-428f-b9da-d71564377bcc)
b- MyDimWaste: Design the dimension table for waste-related data.

c- MyDimZone: Design the dimension table for zone-related data. 

d- MyFactTrips: Design the fact table to store trip-related data. 
Dimension Tables Implementation
Create the MyDimDate dimension table. (2 pts)
Create the MyDimWaste dimension table. (1 pt)
Create the MyDimZone dimension table. (1 pt)
Fact Table Implementation
Create the MyFactTrips fact table. (2 pts)
Data Loading
Load data into the DimDate dimension table. (1 pt)
Load data into the dimension table DimTruck. (1 pt)
Load data into the dimension table DimStation. (1 pt)
Load data into the fact table FactTrips. (1 pt)
Query Development
Create a grouping sets query. (2 pts)
Create a rollup query. (2 pts)
Create a cube query using columns year, city, station, and average waste collected. (2 pts)
Create an MQT (Materialized Query Table) named max_waste_per_station using columns city, station, truck type, and max waste collected. (2 pts)
Dashboard Visualization
Create a pie chart in the dashboard. (1 pt)
Create a bar chart in the dashboard. (1 pt)
Create a line chart in the dashboard. (1 pt)
Create another pie chart in the dashboard. (1 pt)
Usage
To use this project, follow the instructions provided in each task's respective folder. Make sure to complete each task according to the grading criteria.



