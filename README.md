# WasteManagmentDWHAndAnalytics
This project is the final project of IBM course "Getting started with Data Warehousing and BI Analytics"
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

![8-FactTripsQuery](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/7b824dd0-6db8-4bfd-ae4a-2dfbe26810a9)


3rd Stage: Data Loading
Load data into the DimDate dimension. 

![9-DimDateData](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/9250e6e6-5c47-4676-a5aa-55130d960fef)

Load data into the dimension DimTruck. 

![10-DimWasteData](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/b9859182-3a72-4fae-a62e-f00bf50e93e6)

Load data into the dimension DimStation. 

![11-DimStationData](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/0159abba-11d6-435f-8eb8-d5f418569f26)

Load data into the fact FactTrips. 

![12-FactTripsDatat](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/3975c07e-08be-40d3-876b-2dd75a055ceb)

4th Stage: Query the data using postgree SQL to extract the most used aggregations for analytics and reporting

Create a grouping sets query.

![13-GroupingSets](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/b4e44df8-546a-4ac0-a919-fe61f1e87133)

Create a rollup query. 

![14-Rollup](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/39c3c974-c2ce-4394-b037-9b0edb64809e)

Create a cube query using columns year, city, station, and average waste collected. 

![15-cube](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/29044d15-9877-4739-b72f-f46c3264cdbf)

Create an MQT (Materialized Query Table) named max_waste_per_station using columns city, station, truck type, and max waste collected. 

![16-MQT Data](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/5665c204-a5c2-4019-b00d-69ee530923eb)

The Final Dashboard using Cognos Analytics

![photo_2023-09-19_18-00-36](https://github.com/Ataa55/WasteManagmentDWHAndAnalytics/assets/115408306/a3e57ffd-db43-4c8d-96b6-0cbb8f7dfbb8)

 




