# WasteManagmentDWHAndAnalytics
This project is the final project of IBN course "Getting started with Data Warehousing and BI Analytics"
In This repository contains the code and documentation for the Solid Waste Management Data Warehouse project.
The project aims to create a data warehouse that will enable the company to generate various reports related to waste collection and recycling operations across major cities in Brazil.

1st Stage: Dwesigning our DWH:
a- MyDimDate: Design the dimension table for date-related data.

![1-DimDate](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/279d1d08-e74c-428f-b9da-d71564377bcc)

b- MyDimWaste: Design the dimension table for waste-related data.

![2-DimWaste](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/eabe85ea-886e-43fa-97fb-5e7d1cf3b2f1)

c- MyDimZone: Design the dimension table for zone-related data. 

![3-DimStation](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/a9cf4c5d-b287-4877-9e8d-8c3fac6ed463)

d- MyFactTrips: Design the fact table to store trip-related data. 

![4-FactTrips](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/4e0f3522-3b67-4930-bab2-583a35f3563d)

2nd Stage: Tables Creation wist Pstgree sql queries
Creation of MyDimDate dimension table.

![5-DimDateQuery](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/61be9e78-0313-48f6-8276-713b8bed8e35)

Creation of MyDimWaste dimension table. 

![6-DimWasteQuery](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/7a99c272-ca3f-421f-a205-ea27637f4d7e)

Creation of MyDimZone dimension table. 

![7-DimStationQuery](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/9a3a00af-0d49-4c34-b505-6e8b1d8d084e)

Create of MyFactTrips fact table.

![Uploading 8-FactTripsQuery.PNG…]()

3rd Stage: Data Loading
Load data into the DimDate dimension table. 
Load data into the dimension table DimTruck. 
Load data into the dimension table DimStation. 
Load data into the fact table FactTrips. 

Query Development
Create a grouping sets query.
Create a rollup query. 
Create a cube query using columns year, city, station, and average waste collected. 
Create an MQT (Materialized Query Table) named max_waste_per_station using columns city, station, truck type, and max waste collected. 
Dashboard Visualization
Create a pie chart in the dashboard. 
Create a bar chart in the dashboard. 
Create a line chart in the dashboard. 
Create a pie chart in the dashboard. 




