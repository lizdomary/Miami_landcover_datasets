# Miami Land Cover Datasets

This dataset includes tabular and vector data for sites monitored under the Carbon in Urban River Biogeochemistry Project (CURB), which examines how social, built, and biophysical factors influence aquatic functions. CURB's primary objective is to assess how human and environmental controls influence the concentrations, composition, and bioavailability of dissolved organic carbon (DOC) in riverine systems across urban landscapes.

In Miami, landscape characterization used a 400-meter buffer around each site rather than traditional watershed delineation. This approach was necessary due to the absence of StreamStats for Florida and the area's flat topography, tidal and canal influences, and karst geology. The 400-meter buffer was chosen based on preliminary modeling that incorporated key variables (septic system density, stormwater infrastructure density, and impervious surface cover) and their relationship to DOC concentrations in a generalized linear model. This scale offered the best model fit (based on log-likelihood) and best captured the land cover characteristics influencing DOC in Miami's urban and hydrologically complex environment.

Stormwater (stormwater units/km²), septic system (septic units/km²) densities, and primary basin names were calculated using the Summarize Within tool in ArcGIS, based on 2021 Miami-Dade County datasets: the Stormwater Point dataset (Miami-Dade County Open Data Hub, 2015), the DOH Septic Systems dataset (Miami-Dade County Open Data Hub, 2016), and primary basin names ((Miami-Dade County Open Data Hub, 2014). Crop cover was derived from the 2021 National Land Cover Dataset (NLCD; Dewitz, 2023). The distance to the salt line, the inland extent of saltwater intrusion, was calculated as the straight-line distance (in kilometers) from each sampling site to the nearest point along the saltwater interface in the Biscayne Aquifer, using USGS data (Prinos, 2019). The distance to the coast was similarly estimated as the shortest distance (in kilometers) to the NOAA Composite Shoreline (Office for Coastal Management, 2025).

References: 

Dewitz, J. (2023). National Land Cover Database (NLCD) 2021 products [Data set]. United States Geological Survey. https://www.sciencebase.gov/catalog/item/647626cbd34e4e58932d9d4e

Miami-Dade County Open Data Hub. (2014, November 13). Primary Basins [GIS dataset]. https://gis-mdc.opendata.arcgis.com/datasets/7bcebee63784485ba46094d93cda170d_0

Miami-Dade County Open Data Hub. (2015, September 10). Stormwater point [GIS Data set]. https://gis-mdc.opendata.arcgis.com/datasets/MDC::stormwater-point/explore

Miami-Dade County Open Data Hub. (2016, February 19). DOH septic system [GIS Data set]. https://gis-mdc.opendata.arcgis.com/datasets/doh-septic-system/explore

Office for Coastal Management. (2025). NOAA Composite Shoreline – Vectorized shoreline derived from NOAA-NOS coastal survey maps and aerial photographs [Data set]. National Oceanic and Atmospheric Administration (NOAA). https://www.fisheries.noaa.gov/inport/item/48238

Prinos, S. T. (2019). Shapefile showing the approximate inland extent of saltwater interface in the Biscayne aquifer in 2018, Miami-Dade County, Florida [Data set]. U.S. Geological Survey. https://doi.org/10.5066/P9ZIC1O4
