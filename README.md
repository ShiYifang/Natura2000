This repository provides the Jupyter Notebooks and the clipping tools for generating vegetation structure within the Natura2000 sites in the Netherlands using AHN4 datasets. The output of the pipeline is LiDAR metrics at 1 m spatial resolution covering the Natura2000 sites within the Netherlands. 


- The Jupyter Notebooks that were used to calculate LiDAR metrics can be found in the [Notebooks](./Notebooks/) folder, where the grid cell size for normalizing point clouds was set to 1 m, and the features were calculated at 1 m spatial resolution.
- The clipping tool is available at: https://github.com/Jinhu-Wang/Retile_Clip_LAZ.
- The AHN4 data is available at: https://www.ahn.nl/dataroom.
- The shapefile of Natura2000 sites within the Netherlands was retrieved from [Natura 2000 viewer](https://natura2000.eea.europa.eu/), and has been provided in the [shp](./shp/) folder.

