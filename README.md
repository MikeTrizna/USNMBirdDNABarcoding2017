# USNM Bird Barcodes

This repository contains data and code used for the publication "DNA Barcoding, Collection Management, and the Bird Collection in the Smithsonian’s National Museum of Natural History" by Schindel et al.

## Table of Contents of Notebooks:
1. [Initializing the datasets](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Initializing%20the%20datasets.ipynb)
2. [Creating Table 1 -- Sequence record and species counts](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Creating%20Table%201%20--%20Sequence%20record%20and%20species%20counts.ipynb)
3. Alignment and distance commands
4. [Creating species-level distance summaries](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Creating%20species-level%20distance%20summaries.ipynb)
5. [Creating Table 2 -- Species-level summary before and after dataset](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Creating%20Table%202%20--%20Species-level%20summary%20before%20and%20after%20dataset.ipynb)
6. Creating Figure 1 -- Geographic distribution map of sequence records
7. [Creating Figure 2 -- Bivariate plot of maximum divergence between members of a species versus minimum divergence between species for the most similar members of each species](http://nbviewer.jupyter.org/github/MikeTrizna/USNMBirdDNABarcoding2017/blob/master/Creating%20Figure%202%20--%20Bivariate%20plot.ipynb)
8. Creating Supplementary Figure 1: Full Maximum Likelihood tree of USNM Bird dataset

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
