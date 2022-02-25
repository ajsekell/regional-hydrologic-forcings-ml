# regional-hydrologic-forcings-ml
Repo for machine learning models for regional prediction of hydrologic forcing functions. FY22 regions: Delaware River Basin (DRB) region, and Upper Colorado River Basin (UCOL) region.

## Dependencies not on CRAN
The package EflowStats can be installed from github using the following lines in R:
install.packages("remotes")
remotes::install_github("USGS-R/EflowStats")

## Running in Parallel
This pipeline is built to run in parallel. Use the `tar_make_clustermq` function with your desired number of workers (cores) to run in parallel.

note: gages2.1 is currently (As of 12-16-21) being stored in a private repo until it is released to the public.

