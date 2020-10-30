# CNN_Guiglion_et_al_2020

Convolutional Neural Network applied to RAVE stellar spectra

This project is dedicated to stellar spectra analysis, based on a Convolutional Neural-Network (CNN). 
We aim at deriving atmospheric parameters a (Teff, log(g) and [M/H]) and chemical abundances 
([alpha/Fe], [Mg/Fe], [Si/Fe], [Al/Fe] and [Ni/Fe]). For the training sample, 
we use stellar labels from APOGEE DR16 (Ahumada et al. 2020). The stellar spectra are those of 
the 6th data release of the RAdial Velocity Experiment (Steinmetz et al. 2020). 
More details on the project can be found in Guiglion et al. 2020. 
This project allows one to build a series of CNN models, and derive atmospheric parameters and chemical abundances.

The present Jupiter notebook requires: 

numpy '1.19.2'
keras '2.4.0'
panda'1.1.2'
tensorflow '2.3.0'

