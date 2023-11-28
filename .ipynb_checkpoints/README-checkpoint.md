# Investigation of Air Quality in Santa Barbara during Thomas fire event

## Description of the Repository

The repository contains detailed information on how to acquire data from various sources for investigating air quality in the Santa Barbara area during the Thomas Fire. Please note that the actual data is not included in this GitHub repository but can be accessed from the links provided in the Data Citation section of this README. The investigation involves the use of invisible color bands to accurately detect fire areas and visualize the air quality index.

## How the Data is Structured

```├── AQI_Thomas.ipynb
├── LICENSE
├── README.md
└── data
    ├── California_Fire_Perimeters_2017
    │   ├── California_Fire_Perimeters_2017.cpg
    │   ├── California_Fire_Perimeters_2017.dbf
    │   ├── California_Fire_Perimeters_2017.prj
    │   ├── California_Fire_Perimeters_2017.shp
    │   └── California_Fire_Perimeters_2017.shx
    └── landsat8-2018-01-26-sb-simplified.nc

```
## Data Citation

- **False Color Raster Image:**
  - Retrieved from the [Microsoft Planetary Computer catalog](https://planetarycomputer.microsoft.com/catalog).

- **California Shapefile:**
  - Downloaded from [California State GIS Data](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about).

- **Air Quality Data:**
  - [2017 Daily AQI Data](https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2017.zip)
  - [2018 Daily AQI Data](https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2018.zip)


