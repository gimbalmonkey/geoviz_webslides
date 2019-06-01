# Saddleback Geovisualization with Webslides
Bryan Begay
05/31/2019

This Visualization project was created to show a geographic event of interest that includes elements of maps and charts. The weblsides are comprised of 5 slides to geovisualize a forested stand called Saddleback. Saddleback stand is located in the OSU Research forest just nort of Corvallis Oregon. This stand is a research location for my masters project, which involves creating a visualization model with LiDAR point clouds to maximize forest aesthetics in timber harvests.

#### Slide 1

The introductory slide that has a video taken from youtube. The video shows aerial footage of a mixed conifer stand. It should be noted that is not Saddleback Stand.

#### Slide 2

Slide two shows a cartodb basemap that is panning over to Corvallis Oregon.

#### Slide 3

Slide 3 shows the location of Saddleback stand using a stamen terrain basemap. The image pans from the city of corvallis, to Saddleback stands location in the OSU Research Forest.

#### Slide 4

 Slide 4 shows 2001 and 2016 satellite imagery from MODIS and Landsat 7. The spatial resolution from the MODIS imagery was 500 meters and 30 meters for Landsat 7 imagery. The spectral values being plotted are NDVI values aquired from a time series analysis done in Google Earth Engine. CSV data was downloaded from the tables in Google Earth Engine and added as mean monthly values of NDVI for only 2001 and 2016. For both satellite data, 2001 is the earliest complete dataset and 2016 is the latest complete datsets.
![image](/img/MODIS.JPG)
Figure 1. Google Earth Engine MODIS time series analysis chart of NDVI mean by day of year from years 2000-2018.
![image](/img/Landsat.JPG)
Figure 2. Google Earth Engine Landsat time series analysis chart of NDVI mean by day of year from years 2000-2017.


### Slide 5.

Slide with Acknowledgements. Background video is a video loop of a false color image with band configuration being NIR, red, and green. The Video loop is from 1991 to 2011 and is positioned directly over Saddleback stand.


#### Other elements:
* Favicon icon
* Dynamic fonts

#### Acknowledgements
Bo Zhao: Instructor
CartoDB: basemap
Stamen: terrain basemaps
Google Earth Engine: Data
