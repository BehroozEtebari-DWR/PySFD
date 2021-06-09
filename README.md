# PySFD
Jupyter Notebooks for Stream Flow depletion factors (Analytical approaches)
Was written for the California Dept. of Water Resources
Modeling and Tools Support Section

for following analytical models:
Glover & Balmer 1954
Hunt 1999
Hantush 1965
Jenkins 1968
Singh 2003
Hunt 2003 ( has not been finilizied yet and need some adjustment for the Stehfest algorithm )

Also Glover-GIS Notebook was developed for Mark West Creek(HUC12) with AVARAGE monthly pumping rates, NHD datasets and 
Water Wells were adopted from following report:
https://www.coastrangewater.org/projects
To implement gis application, I used Geopandas library
Users need to create a new environemt inside Anaconda, then activate the new environment and run Glover-GIS:
Here is the instructions for Geopandas:
conda create -n geo_env
conda activate geo_env
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install python=3 geopandas


