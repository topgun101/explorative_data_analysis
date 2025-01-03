# Geo-spatial Data and Interactive Visualizations
Github: https://github.com/topgun101/explorative_data_analysis

## Features and running instructions
- clone the repository
- open **geo_data_visuals.ipynb** in jupyter notebook
- ensure that all required libraries are installed
- run all cells
  - this should result in showing the choropleth map as well as the supporting visualizations
  - the generated map is stored in a folder "maps", which should be generated during the first run 
  (this ensures faster loading time for later usage)
  - it is also possible to pre-generate all maps for all years at once by uncommenting the **"generate_all_maps()"** function
  - when changing the slider to a specific year the maps are generated for this year.
  This process may take a little while if there are no pre-generated maps available.
