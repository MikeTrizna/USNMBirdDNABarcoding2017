# USNM Bird Barcodes

This repository contains data and code used for the publication "DNA Barcoding, Collection Management, and the Bird Collection in the Smithsonian’s National Museum of Natural History" by Schindel et al.

## Table of Contents of Notebooks:
1. Creating Table 1 -- Sequence record and species counts
2. Alignment and distance commands
3. [Creating species-level distance summaries](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Creating%20species-level%20distance%20summaries.ipynb)
4. Creating Table 2 -- Species-level summary before and after dataset
5. Creating Figure 1 -- Geographic distribution map of sequence records
6. Creating Figure 2 -- Bivariate plot of maximum divergence between members of a species versus minimum divergence between species for the most similar members of each species
7. Creating Supplementary Figure 1: Full Maximum Likelihood tree of USNM Bird dataset

## Data
The "data" directory contains input data files that are used for analyses documented by the various Jupyter notebooks. Please refer to the README file in the data directory for a full description of all files there (and also files that were too large to be stored in GitHub).

## Required Software
### Command-line bioinformatics tools
* Alignment was done using MAFFT version .
* Distance calculations were done using Mothur version 
* Maximum Likelihood Tree was created using FastTree version

### Executing Jupyter Notebooks
The .ipynb files are Jupyter notebooks, which can be downloaded and executed if you have Python and Jupyter installed on your computer. There are also a few required Python libraries, and you can install these by running:
pip install requirements.txt
### Python libraries used
* Ete3 used to annotate and visualize trees produced by FastTree
* Pandas used to read in distance files and calculate species distance summaries
* Basemap and Folium used to create distribution maps
* Seaborn and Bokeh used to create species inter/intra-specific distance plots
