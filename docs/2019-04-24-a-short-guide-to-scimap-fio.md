---
title: "A short guide to SCIMAP-FIO"
date: "2019-04-24"
---

  
Instructions when logged in:

The dashboard at log-in will a split into 4 windows – each one labelled (DEM, rainfall etc). The bottom right is a FIO burden map (obfuscated to hide spatial data we were given for livestock numbers across Scotland, England and Wales). When the model runs it uses real data not the fuzzy E. coli land burden you will see. Usual caveats of spatial data apply – livestock numbers are linked to a Business Reference Number – we have no idea if the livestock are really kept within that farm boundary or elsewhere so usual assumptions apply. Data for livestock numbers varies in terms of resolution – highest resolution for Scotland (BRN level), lower for Wales (2km grids), even lower for England (5km grids).

You may well be familiar with the original SCIMAP but just as a recap and now with info for the FIO predictions: You’ll see that there is a purple banner across the top of the dashboard – and on the right are a series of tabs. For having a play you really only need to use the ‘catchments’ tab, ‘build’ tab and ‘results’ tab.

Over on the left panel you will see ‘create new catchment’

Steps:

A.        Catchments Tab

1.         Select ‘Create New Catchment’

2.         Enter a Catchment ‘Name’

3.         Specify a Drain Point on the map (zoom in and select a point on the drainage network – be careful not to extend too far out into the coast, keep landward)

4.         Click ‘Calculate’

5.         Once the catchment is completed, click ‘Save’ (check you have a sensible catchment shapefile) – after its saved your catchment will appear on all four windows on the dashboard

B.        Build Tab

1.         Provide a name for this simulation (same name as your catchment name ?)

2.         Select an existing catchment (ie your saved catchment shapefile)

3.         Select ‘Use FIO Seasonal Set’

4.         Select a season (actually a month of your choosing rather than a season) from the Seasons drop-down box

5.         Click ‘Run SCIMAP’

Notes

‘Max Annual’ provides the highest FIO burden within the year.

When selecting a month: the rainfall data (long term 30 yr average) for that month is used, as well as the FIO values from the 1st day of the specified month.

C.        Results Tab

1.         On the left panel on the results tab you will see ‘results set’ – scroll to the bottom of that result set and you see progress of your catchment run

2.         Once the simulation is complete the results will be visible on this page.

3.         Sometimes the run leaves you hanging after it gets to ‘complete’ – refresh your page and click back on the results tab, select your catchment.

4.         ‘In channel risk’ is based on relative risk attributed to E. coli delivery to stream where red areas represent the highest risk, and blue areas the lowest.

5.         The build summary will indicate which simulation was run and with which parameters.

6.         Various layers can be added and removed using the layer switcher in the top right (channel accumulated risk is basically E. coli risk, FIO burden is obfuscated land loading of E. coli, the rest are self-explanatory in terms of hydrological connectivity, erosion etc)

7.         Results sets can be deleted with the ‘Delete Selected’ button

8.         Results can be downloaded using the buttons at the bottom of the tab.
