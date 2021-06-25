# UV-Vis-PL-to-bandgaps

The first portion of this codes will extract the bandgaps from the UV-Vis spectroscopy data by cleaning, normalizing, scaling and converting it to Tauc plots. Furthermore, we add an appropriate trend line to the linear region of the Tauc plots and find the intercept for extracting the bandgaps. 

The second portion of the code will extract the bandgaps from the Photoluminescence spectroscopy data by first doing the baseline correction using adaptive iteratively reweighted penalized least squares and then normalizing and finding the appropriate peaks.
