
# Homework 4 - Visualizing Fire Scars from the Eaton and Palisades Fires 

![Palisades Fire Aerial Image](https://ca-times.brightspotcdn.com/dims4/default/47f6d3e/2147483647/strip/true/crop/6000x4000+0+0/resize/2000x1333!/quality/75/?url=https%3A%2F%2Fcalifornia-times-brightspot.s3.amazonaws.com%2F01%2F51%2F8fbb40af428eacb8328513e7cf7a%2F1490019-me-0109-palisades-aerials-rcg-2593-enhanced-nrb.jpg)
Photo by Robert Gauthier, Los Angeles Times.


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

- County of Los Angeles. “Palisades and Eaton Dissolved Fire Perimeters.” ArcGIS Hub, 2025, https://hub.arcgis.com/maps/.

- Fry, Hannah, et al. “Los Angeles Has Never Seen This Level of Destruction: ‘Everything Is Burned Down.’” Los Angeles Times, 10 Jan. 2025, https://www.latimes.com/california/story/2025-01-10/the-destruction-in-pacific-palisades-is-at-a-level-los-angeles-has-never-seen-everything-is-burned-down.

- NASA. “Why Is That Forest Red and That Cloud Blue? How to Interpret a False-Color Satellite Image.” NASA Earth Observatory, 8 Dec. 2025, https://science.nasa.gov/earth/earth-observatory/how-to-interpret-a-false-color-satellite-image/.

- U.S. Geological Survey. “Landsat Collection 2 Level-2.” Microsoft Planetary Computer, 2025, https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2.


