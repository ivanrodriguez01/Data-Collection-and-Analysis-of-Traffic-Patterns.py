# MVC_First_of_the_Year_Block_Group

This project is based on the Massachusetts Vehicle Census (MVC) that joins Vehicle-Level odometer, readings  with attribute and registration transaction histories. This powerful resource allows policymarkers, researchers, and other stakeholders understand state and local trends in vehicle usage and ownership.

The Massachusetts Vehicle Census First of the Year Block Group dataset contains historical point in time snapshots of the amount of vehicles and estimated daily VMT (Vehicle Miles Travelled) grouped by BlockGroup, municipality and vehicle attribute. The dataset uses excise tax data and annual vehicle inspection odometer readings ad data inputs. 

[https://geo-massdot.opendata.arcgis.com/datasets/mvc-first-of-the-year-block-group/about](https://geo-massdot.opendata.arcgis.com/datasets/mvc-first-of-the-year-block-group/about) Website where to get the data.

## Data information 
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

| # of Column | Column Name | Column type |
| ----------- | ----------- | ----------- |
| 0 | Date | object |
| 1 | MPO | object |
| 2 | GarageCode  | int64 |
| 3 | Municipality | int64 |
| 4 | BlockGroup | float64 |

 5   VehicleType          object 
 6   AdvancedVehicleType  object 
 7   FuelClass            object 
 8   VehicleUse           object 
 9   ModelYear            int64  
 10  GVWRCategory         object 
 11  Count                int64  
 12  DailyVMT             float64
dtypes: float64(2), int64(3), object(8)

These are the columns and the type on them, there are in total 2,723,702 rows and 13 columns on it, so if the data were perfect there would be 35,408,123 records on the table.
