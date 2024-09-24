# Reconstruction of Sea Surface Salinity from observations made by the SMOS satellite in the southwest Atlantic Ocean
Datasets, codes and outputs used in the Master's Thesis of the Master's Degree in Advanced Physics and Applied Mathematics at University of the Balearic Islands (UIB)
## Description
The aim of this work is to improve the SSS satellite observations ressolution using a Lagrangian reconstruction technique to detect mesoscale salinity fronts at the southwest region of the Atlantic Ocean. The validation of the reconstructed fields is made with termosalinograph in-situ data from oceanographic campaigns.
## OceanParcels installation
The particle tracking simulation is done using OceanParcels whose installation manual can be found here: https://docs.oceanparcels.org/en/latest/installation.html
## Repository structure
### `codes`
Folder with python scripts and Jupyter notebooks used in the project. 
### `data`
All datasets used in the project organized as follows:
- `insitu_data`: in-situ datasets from thermosalinograph.
- `SSS_data`: SSS map products
- `velocity_data`: geostrophic currents derived from altimetry
### `outputs`
Outputs from scripts.
- `sim`: particle coordinates after the backward advection (.zarr format)
- `sim_tagged`: maps with advected SSS
- `sim_interpolation`: interpolated advected SSS at the coordinates of in-situ data
- `SMOS_interpolation`: interpolated SMOS SSS at the coordinates of in-situ data
### `plots`

