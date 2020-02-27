---
title: "Land cover risk weights?"
date: "2011-03-17"
---

Questioner:

Have you got any info on the landcover map and the weightings given to each landcover type and how these have been calculated?

Help:

For the land cover data we tend to use the CEH LCM2000 but an alternative would be the CORINE data. In both cases we reclassify the data into the following categories:

- Horticulture = 1
- Arable = 1
- Grassland = 0.1
- Improved Grassland = 0.2
- Heath / peat / bog = 0.05
- Woodland 0.00
- Urban = 0.00

In terms of how we come to them, here is some text from the SCIMAP final report:

"The erodibility of fine sediment pei is specified logically with respect to the probability that the catchment has bare ground associated with a given land use. We make some basic assumptions about the effects of land use upon erodibility:

1) erodibility might be expected to be negligible or zero under woodland cover (pei =0.00);

2) it might rise slightly under moorland (pei =0.05);

3) rise again under extensive pasture (pei =0.10);

4) rise again under intensive or improved pasture (pei =0.20); and

5) rise significantly, to be the highest, for any land use (e.g. arable)

where there is a risk of the land cover being bare for part of the year (pei =1.00)."
