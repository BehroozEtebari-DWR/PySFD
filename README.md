# PySFD
Jupyter Notebooks for Stream Flow Depletion (SFD) analyses (Analytical approaches)
Was written for the California Dept. of Water Resources
Modeling and Tools Support Section

for following analytical models:
1-Glover & Balmer 1954
2-Hunt-1999
3-Hantush-1965
4-Jenkins-1968
5-Singh-2003
6-Apportionment via GIS(Geopandas), closest stream distance
7-Hunt 2003 (has not been finilizied yet and need some adjustment for the Stehfest algorithm )

Also Glover-GIS Notebook was developed for Mark West Creek(HUC12) with AVARAGE monthly pumping rates, NHD datasets and 
Water Wells were adopted from following report:
https://www.coastrangewater.org/projects
To implement gis application, I used Geopandas library
Users need to create a new environemt inside Anaconda, then activate the new environment and run Glover-GIS:
Here is the instructions for Geopandas:
1- conda create -n geo_env
2- conda activate geo_env
3- conda config --env --add channels conda-forge
4- conda config --env --set channel_priority strict
5- conda install python=3 geopandas


