## ParaView-Yellowstone

[ParaView](https://www.paraview.org/download/) project for plate tectonics and volcanism study on Yellowstone area, USA.

## Provided datasets ([EPSG:32613 WGS 84 / UTM zone 13N](https://epsg.io/32613))

  * grav_28.1.subset.32613.8km_b_gamma40.0km,60.0km.anomaly.vtk - our density anomaly model by inversion of [Sandwell and Smith Gravity Anomaly and Vertical Gravity Gradient Open Datasets at 1 arc-minute resolution](https://www.linkedin.com/pulse/sandwell-smith-gravity-anomaly-vertical-gradient-open-pechnikov/) with bandpass filter 40-60km.

  * wsm.32613.* - [World Stress Map 2006](http://doi.org/10.5880/WSM.2016.001)

  * eq_us.fixed.csv, eq_us.32613.vtm - [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/)

  * volcanoes.32613.vtm - [SMITHSONIAN INSTITUTION GLOBAL VOLCANISM PROGRAM](https://volcano.si.edu/) (Smithsonian_Global_Volcanism_Program_List_v4.3.4.xls)

  * AOI.32613.vtu - [GEBCO_2019 Bathymetry Grid is Open dataset at 15 arc-second resolution](https://www.linkedin.com/pulse/gebco2019-bathymetry-grid-open-datasets-15-arc-second-pechnikov/)

## How it looks

![ParaView Project Screenshot](paraview_project.jpg)

# How to open the project

Use [ParaView](https://www.paraview.org/download/) File -> Load State menu item to load the project.pvsm project file and specify "data" subdirectory as "Data Directory".

## Authors

A.V.Durandin
https://orcid.org/0000-0001-6468-9757 (ORCID)
E-mail: durandin.andrew@gmail.com

A.O.Pechnikov
https://orcid.org/0000-0001-9626-8615 (ORCID)
E-mail: pechnikov@mobigroup.ru
