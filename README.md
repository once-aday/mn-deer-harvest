# Deer Harvest - Total Harvest Review and Possible Associations with Chronic Wasting Disease

## Objectives
  - Compile data and observe state-wide trends on Total Deer Harvest
  - Map Year by Year Changes in Harvest Numbers
  - Map and Explore Chronic Wasting Disease relative to Deer Harvest
  
This project utilizes jupyter notebook for initial data processing and for fostering rapid insights. It Follows up with a web map displaying the notebook products allowing users to explore the data on their own in the comfort and adaptabiltiy of the browser-map environment.

The subject of the data is Deer harvest in Minnesota; Looking at historical yearly datasets and how the available data we have on the devestating Chronic Wasting Disease can be integrated with it to drive insights and potential action.

The Notebook has features to automatically generate maps based on a folder of shapefiles. In this case, yearly deer harvest data is released as individual shapefiles, so theoretically when 2020 data becomes available it can be placed in the 'notebooks/data/deer_harvest_shp' directory and the maps and stats for that year will be displayed in the notebook and web map.


Notebook Environment:

A shared conda environment file, **mn-deer.yml**, to run this notebook is available in the root directory of this repo.

libraries of note installed:

matplotlib
geopandas
mapclassify
jupyter
