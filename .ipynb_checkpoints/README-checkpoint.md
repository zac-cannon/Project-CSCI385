# MTA Open Data Challenge

## Requirements
- Clone my github repository
- pip install plotly geopandas contextily

## What is the MTA Open Data Challenge?
A competition where participants develop a project that utilizes the MTA’s open datasets.
The challenge aims to showcase how open data can be utilized to improve urban mobility, transportation efficiency, and community engagement.
For my project I aim to use python and various libraries in order to:
- Analyze Post-Pandemic Ridership trends and Subway Delays
- Plot useful location data

## Post Pandemic Trends
Dataset: Total Ridership Data since the Pandemic
Created multiple plots using plotnine and one plot with an interactive slider using plotly express.
The MTA rider numbers have not yet returned to pre pandemic levels and Subway Ridership has grown more than Bus Ridership.

## Subway Delay Patterns
Dataset: Subway Trains Delayed since 2020
Created an interactive graph, density heatmap, and sunburst chart using plotly express.
Certain factors such as Crew Availability and Maintenance, have a significantly higher impact on subway delays than other factors.

## Plotting Useful Location Data
Datasets: Subway Entrances and Train Routes.
Plotted transit stop locations with entrance types using contextily and matplotlib.
Graphed Train routes and calculated distances using geopandas

## Using Contextily & Geopandas 
Contextily allows you to add basemaps (OpenStreetMap) to geospatial plots that correspond to coordinates.
Geopandas expands on Pandas handle spatial data by creating a GeoDataFrame to store spatial data with columns for geometries(points, lines, polygons)
