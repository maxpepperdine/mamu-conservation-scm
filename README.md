# Delineating suitable nesting habitat for marbled murrelets in the Santa Cruz Mountains

## Description

This analysis was completed as part of a quarter-long project to develop a conservation plan in ESM 270p (Conservation Planning Practicum) at the [Bren School of Environmental Science & Management](https://bren.ucsb.edu/) at the University of California, Santa Barbara. The project focused on delineating suitable nesting habitat for the marbled murrelet (Brachyramphus marmoratus) following severe wildfires in the Santa Cruz Mountains (SCM). 

## Repository organization

```
├── data
|    └── new_data
|         └── ...
|    └── raw_data
|         └── ...
├── scripts
|    └── distance_to_nearest_river.qmd          # create the distance to nearest river raster
|    └── distance_to_ocean.qmd                  # create the distance to ocean raster
|    └── figure_making.qmd                      # make figures for the manuscript
|    └── land_prioritization_arcgis.qmd         # visualize results from prioritization in ArcGIS Pro
|    └── land_prioritization.qmd                # prioritize county parcels for murrelet conservation
|    └── mamu_occurrence_data.qmd               # upload, clean, and filter GBIF occurrence data
|    └── maxent_prefire_cdfw.qmd                # run MaxEnt models with pre-fire CDFW data
|    └── maxent_prefire_gbif.qmd                # run MaxEnt models with pre-fire GBIF data
|    └── maxent_postfire_gbif.qmd               # run MaxEnt models with post-fire GBIF data
|    └── maxent_wallace_variable_prep.qmd       # make preictor variables suitable for Wallace
|    └── pacific_veg_map_processing.qmd         # process & resample all Pacific Veg Map data
|    └── running_wallace.qmd                    # activate the `Wallace` package for MaxEnt exploration
├── .gitignore                                  # used to avoid pushing all data to GitHub
├── README.md
├── mamu-conservation-scm.Rproj                 # R project file
```

## Data access

The data used in this analysis was too large to upload to GitHub. 

Tabular organization of metadata for the environmental predictor variables with links to accessing the data can be found [here](https://docs.google.com/spreadsheets/d/1AY5dmmMqd9WtNLHPuMkyDuuBdDyJMXatRGR2f7uCAwE/edit?usp=sharing). Occurrence data for the marbled murrelet was obtained from the [Global Biodiversity Information Facility (GBIF)](https://www.gbif.org/). 

## Acknowledgements 

This assignment was created and organized Ashley Larsen, an Associate Professor at the Bren School and the instructor for ESM 270p. ESM 270p (Conservation Planning Practicum) is offered in the [Master of Environmental Science & Management (MESM)](https://bren.ucsb.edu/masters-programs/master-environmental-science-and-management) program at the Bren School as one the foundational courses for the [Conservation Planning](https://bren.ucsb.edu/masters-programs/master-environmental-science-and-management/academics-mesm/specializations/conservation) specialization.






