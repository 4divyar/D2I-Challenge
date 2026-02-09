# Data Assets
This folder contains original and cleaned datasets, the scripts used to clean them, the final curated data asset, and a Data Card.
## Folder Descriptions
- Raw Data: Holds all the shapefiles (state and county) and raw datasets for all environmental factors. 
- Cleaning: Holds the scripts and notebooks that were used to clean and merge datasets. 
## Data Dictionary for `final.csv`
| Column Name                     | Data Type | Description |
|---------------------------------|-----------|-------------|
| GEOID                            | int  | Unique identifier for each county |
| County                           | str       | Name of the county |
| State                            | str       | State abbreviation (e.g., CA, TX) |
| State Name                       | str       | Full name of the state |
| Wildfire Hazard Potential Score  | float     | Score representing wildfire hazard |
| Drought Risk Score               | float     | Score representing drought risk |
| Wind Plant Capacity              | float     | Installed wind energy capacity |
| Oil Production Quantity          | float     | Oil production |
| Gas Production Quantity          | float     | Gas production |
| Latitude                         | float     | Latitude coordinate of county centroid |
| Longitude                        | float     | Longitude coordinate of county centroid |
| geometry                         | object    | Geospatial geometry of the county (point) |
| Pareto Efficient                 | bool      | True if county is Pareto efficient |
| cn geometry                      | object    | Another geospatial geometry column (polygon) |

