# California Coastal Chaparral Live Fuel Moisture Dataset (1987-2019)

## Overview
This repository contains the processing notebooks used to create a historical (1987-2019), 1km resolution live fuel moisture (LFM) dataset for California coastal mountain chaparral from San Luis Obispo to the edge of Los Angeles. The dataset includes LFM values for the following species:
- Chamise
- Old growth chamise
- Black sage
- Bigpod ceanothus

## Dataset Access
The complete dataset will be publicly available on Dryad:  
*(in preparation)*

## Publication
A detailed publication describing the dataset creation methodology is forthcoming:  
*(in preparation)*

## Repository Structure
The notebooks in this repository are numbered sequentially for systematic processing. Each notebook represents a distinct step in the dataset creation pipeline.

## Species Information
The dataset focuses on key chaparral species in California's coastal mountain regions:
- **Chamise** (*Adenostoma fasciculatum*)
- **Black sage** (*Salvia mellifera*)
- **Bigpod ceanothus** (*Ceanothus megacarpus*)

## Dataset Specifications
- **Temporal Coverage**: December 1987 - June 2019
- **Spatial Resolution**: 1km
- **Geographic Extent**: California coastal mountain regions from San Luis Obispo to the edge of Los Angeles
- **Data Format**: NetCDF

## Model Details
The random forest models for dataset creation use the following predictor variables:
- 90-day accumulated precipitation
- 90-day mean temperature
- 150-day mean solar radiation
- Day length
- Near Infrared Reflectance of Vegetation (NIRv)
- 7-day mean soil moisture
- 150-day mean relative humidity
- 90-day climatic water deficit
- 30-day accumulated precipitation
Eight of the predictor variables were calculated from a previously constructed WRF climatology available [here](https://clivac.eri.ucsb.edu/clivac/SBCWRFD/index.html)
NIRv was downloaded using a Google Earth Engine script available [here](https://code.earthengine.google.com/b01c871bf7cb81aaf11e7423dd06781a)

## Contact
For questions about the dataset or processing methodology, please [create an issue](../../issues) in this repository.

## Citation
When using this dataset, please cite:  
*(citation information will be added upon publication)*

## License
[Specify your license here]
