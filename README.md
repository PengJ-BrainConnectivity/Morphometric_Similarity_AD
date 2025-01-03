# Morphometric Similarity in Psychosis- data and code


[![DOI](https://zenodo.org/badge/151554225.svg)](https://zenodo.org/badge/latestdoi/151554225)

This repository contains code to analyse morphometric similarity matrices from patients with schizophrenia and healthy control subjects, as reported by [Morgan et al, 2019](https://doi.org/10.1073/pnas.1820754116). Please cite that paper if you find this code helpful in your own analyses. The PLS code to relate gene expression to the neuroimaging signal was written by Dr Petra Vértes and introduced in [Whitaker and Vértes et al, PNAS 2016](http://www.pnas.org/content/113/32/9105) and [Vértes et al, Philosophical Transactions of the Royal Society B](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2015.0362), please cite those papers if you this approach in your own work.

The Yeo network mapping ('Schaefer2018_100Parcels_17Networks_order.txt') was performed to show the segmentation regions.[B. T. Thomas Yeo* et al, Journal of Neurophysiology, 2011] [Váša et al, Cereb Cortex. 2018](https://doi.org/10.1152/jn.00338.2011).

The code is written in [MATLAB](https://uk.mathworks.com/products/matlab.html). Data to go with the code can be downloaded [here](https://doi.org/10.6084/m9.figshare.7908488.v1). The code is split into two main files- 'MS_analyses.md' contains the code needed to construct the morphometric similarity matrices and analyse the global and regional differences in MS between control subjects and patients, 'Gene_analyses.md' contains the code needed for the gene analyses (building on inputs from 'MS_analyses.md').
