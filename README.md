# MVC_First_of_the_Year_Block_Group

This project is based on the Massachusetts Vehicle Census (MVC) that joins Vehicle-Level odometer, readings  with attribute and registration transaction histories. This powerful resource allows policymarkers, researchers, and other stakeholders understand state and local trends in vehicle usage and ownership.

The Massachusetts Vehicle Census First of the Year Block Group dataset contains historical point in time snapshots of the amount of vehicles and estimated daily VMT (Vehicle Miles Travelled) grouped by BlockGroup, municipality and vehicle attribute. The dataset uses excise tax data and annual vehicle inspection odometer readings ad data inputs. 

[https://geo-massdot.opendata.arcgis.com/datasets/mvc-first-of-the-year-block-group/about](https://geo-massdot.opendata.arcgis.com/datasets/mvc-first-of-the-year-block-group/about) Website where to get the data.

## Data information 

| # of Column | Column Name | Column type | # of Unique values |
| ----------- | ----------- | ----------- | ------------------ |
| 1           | Date        | object |
| 2 | MPO | object |
| 3 | GarageCode  | int64 |
| 4 | Municipality | object |
| 5 | BlockGroup | float64 |
| 6 | VehicleType | object |
| 7 | AdvancedVehicleType | object |
| 8 | FuelClass | object |
| 9 | VehicleUse | object |
| 10 | ModelYear | int64 |
| 11 | GVWRCategory | object |
| 12 | Count | int64 |
| 13 | DailyVMT | float64 |  

***dtypes: float64(2), int64(3), object(8)***

These are the columns and the type on them, there are in total 2,723,702 rows and 13 columns on it, so if the data were perfect there would be 35,408,123 records on the table.

Some values are missed in the **BlockGroup** column. There are 516 values missed, I'll get rid of those rows to work with the rest of the data.
New data rows equal to 2,723,186 rows and 13 columns.

### 1. Date information


