---
title: "Resolving different grid systems in SAGA GIS"
date: "2011-03-17"
---

Questioner:

I have used spatial analyst to cut the DEM, landcover map and annual average rainfall layers and save all of these as ascii files.  They all load into SAGA and you can do all the operations you like on them individually but they are slightly different grid systems and different spatial units so I cannot get them to combine.  For example, trying to run the fine sediment module, if I set the grid system to the one which the DEM is in, I can add that, but I cannot add the other two layers because they are not options within that grid system.  How do I fix this?

Help:

The easiest way to fix that is to use one dataset as the template to bring the other datasets into. The best thing to do is probably to import a shapefile of your catchment outline

File > shapes > load shapes

Then you can use the shapefile to clip each of the raster datasets (DTM, LCM, rainfall).

In the Modules tab click Shapes – Grid then double click on Clip Grid with Polygon

Click in the box to the right of Grid system choose the grid system you want to stick with

Click in the box to the right of >> Input choose your grid

e.g. \[catchmentname\]\_dtm\_10

Click in the box to the right of >> Polygons choose your catchment polygon

e.g. Watershed Basins

Click Okay

 

This is taken from the SCIMAP-SAGA user guide, which runs through the full workflow for SCIMAP, it has quite a few useful examples of how to do things in SAGA.
