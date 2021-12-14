# Timing and magnitude of climate driven range shifts in transboundary fish stocks challenge their management


This repository is intended to support the project *Timing and magnitude of climate driven range shifts in transboundary fish stocks challenge their management* 

**Authors**: Juliano Palacios-Abrantes<sup>1,6</sup>, Thomas L. Frölicher<sup>2,3</sup>, Gabriel Reygondeau<sup>1</sup>, U. Rashid
Sumaila<sup>1</sup>, Alessandro Tagliabue<sup>4</sup>, Colette C.C. Wabnitz<sup>1,5</sup>, and William W.L. Cheung<sup>1</sup>

1- Institute for the Oceans and Fisheries, University of British Columbia, Vancouver, Canada. 

2- Climate and Environmental Physics, Physics Institute, University of Bern.

3- Oeschger Centre for Climate Change Research, University of Bern, Switzerland.

4- School of Environmental Sciences, University of Liverpool.

5- Stanford Center for Ocean Solutions, Stanford University, Stanford, United States"

6- Center for Limnology, University of Wisconsin-Madison, United States



\*Corresponding author: Juliano Palacios-Abrantes, j.palacios@oceans.ubc.ca


# Project Goal:

- Determine the changes in in range shift of transboundary species 

# Files and folders organization:

In this repository you will find all of the code related to the manuscript *Matching the Time of Emergence of Transboundary Fish Stocks to Lead Time for Policy Response Under Climate Change*. **Note** that the code needs to compile data from external sources. Due to the large volume of data, these are not in *GitHub*. Please email me to discuss other ways to share the data.

## Scripts

This folder holds the cripts related to the project

- **Initial_Analysis.Rmd**: This is the *RMD* where all the data analysis for the manuscript can be found

- **Manuscript_draft.RMD**: An eraly version of the manuscript (draft) to be submitted as a PDF or word document

- **Supplements.RMD**: Supplement draft to be submitted as a PDF or word document

## References

Documents needed for the references of the manuscript including the reference list

- **ToE_Ref.bib**: list of bibliography used in the project
- **gcb.csl**: Reference form according to the journal where the manuscript was published

# Figures

Here you will find all of the figures, main and supplemental, that were published alongside the project

# Tables

Here you will find all of the tables, main and supplemental, that were published alongside the project in *.csv* format

## Data availabillity 

All the data used to generate the results of the current project are freely available in their respective repositories. In the `Data` folder you will find the data *created* by this project. See below for instructions on how/where to collect the *raw* data used. Feel free to contact me for this purpose and I will do my best to help you get these data. 

### `Data` folder

#### Results

- **toe_data.csv**: This is the data set referent to the time of emergence of each stock. This is the main dataset to generate figures 2-4. Please contact me for disaggregated data.

- **ssr_data.csv**: This is the data set referent to the change in stock share ratio averaged by EEZ. This is the main data set to generate figures 5-6. Please contact me for disaggregated data.

#### Support data

- **sau_matching_names.csv**, This is a cross-reference list of spatial entities between the Sea Around Us data, the United Nations data and Natural Earth shapefiles. 

- **eez_centroids.csv**, This data set contains the centroids (latitude and longitude) of the EEZs

### External Data

These *external* data are found along the [`Initial_analysis.Rmd`]() script. In all cases they are publicly available, but I do not own them so I am not allowed to make them available for the public. 

- **Transboundary_spp.csv**, This is the list of transboundary species identified by Palacios-Abrantes *et al*., 2020 and can be retrieved from the project's github [FishForVisa](https://github.com/jepa/FishForVisa/tree/master/Data/Results) 

- **exploited_species_list.csv**, This list references the `taxon_key` with the `taxon_sci_name`. Can be extracted from `toe_data.csv`

- **Neighbours_eez_id.csv**, This is the list of neighbouring EEZs Can be extracted from `toe_data.csv` 

- **sau_catch_value_country_taxon_JEPA.csv**, This is the *Sea Around Us* catch and value data within the world EEZs. Please contact the [SAU](http://seaaroundus.org) for data access.

- **DBEM and GFDL raw ensemble data**, Please contact Dr. William Cheung at The Institute for the Oceans and Fisheries ([IOF](https://oceans.ubc.ca/william-cheung/)) for further discussion of the DBEM raw data. 

#### Shapefiles

- **SAUEEZ_July2015.shp**, This is the *Sea Around Us* shapefile used to estimate the EEZ's centroids and presented in figures 3-5. See [Figure S1](https://github.com/jepa/EmergingFish/blob/gcb_rev/Figures/FigS1.png) for a graphical representation of the shapefile an contact the [SAU](http://seaaroundus.org) for a version. 

*Final note*. If you are interested in any data used in this research I encourage you to contact me so we can further discuss ways to move forward. 


