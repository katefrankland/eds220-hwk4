
# Homework 4 - Visualizing Fire Scars from the Eaton and Palisades Fires 

## About 
The purpose of this notebook is to visualize the Eaton and Palisades fires that took place in Los Angeles County in 2025. False color imagery is used to overlay the two fire perimeters and see where burn scars are present. This is important because infrared bands can help distinguish burned areas better than true color imagery.

## Highlights
 - Using 'xarray' and 'rioxarray' to explore data and restore the coordinate reference system (CRS).
 - Exploring false color imagery using infrared bands to see where burn scars are present.
 - Reprojecting both fire perimeters to match the raster CRS and then overlaying them to the false color image.

## Repo Structure 

```
eds220-hwk4
├── README.md
├── .gitignore
├── data/
│   ├── eaton_data/
│   ├── palisades_data/
│   └── landsat8-2025-02-23-palisades-eaton.nc
├── hwk4-task2-false-color-frankland.ipynb
└── hwk4-task2-false-color-frankland.pdf

```

## Data

For this assignment, Landsat 8 satellite data and Perimeter data for the Palisades and Eaton fires are being used. 

**Landsat 8 Satellite Data** was provided in a Google Drive link for the purpose of this assignment, but was originally sourced from the Microsoft Planetary Computer data catalog. This data uses five different bands, and is focused on the Los Angeles County area for the visualization. 

**Palisades and Eaton Fire Perimeter Data** is sourced from ArcGIS, providing fire boundary information. The files are stored in 'data/eaton_data/' and 'data/palisades_data'.

## References 
# References

- County of Los Angeles. (2025). Palisades and Eaton dissolved fire perimeters. ArcGIS Hub. [ArcGIS link]("https://hub.arcgis.com/maps/")

- NASA. (2025, December 8). Why is that forest red and that cloud blue? How to interpret a false-color satellite image. https://science.nasa.gov/earth/earth-observatory/how-to-interpret-a-false-color-satellite-image/

- U.S. Geological Survey. (2025). Landsat Collection 2 Level-2. Microsoft Planetary Computer. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2