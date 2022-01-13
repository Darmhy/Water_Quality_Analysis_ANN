# Water Quality Analysis (Artificial Neural Network)

### Introduction
With the approximate contribution of half of the productivity of the marine ecosystem, Phytoplankton is identified as an essential pillar of the food web, producing organic elements and energy for higher trophic levels [(Ref - Ok et al., 2021)](https://www.frontiersin.org/article/10.3389/fmars.2021.681252). However, the excessive presence of this plant results in the decolouration of the water body, leading to the death of marine life and sickness in humans. Assessing and accurate predictions of Phytoplankton bloom will aid the application of preventive and corrective measures to minimize the effect.

### Project Aim and method
This project uses [CEFAS’ 2022 data](https://www.cefas.co.uk/data-and-publications/habs/england-and-wales-biotoxins-and-phytoplankton-results-2022/) on biotoxins and phytoplantkon to explore patterns of higher or lower concentration of either (or both) according to features provided. 
Data on phytoplankton is presented on the second tab of the xlsx file provided. 
The acquired data was cleaned and then used in training a multi-layer feed-forward neural network to predict from a set of input features whether the phytoplankton level detected is above the threshold specified (first tab of the file). 

### Details and accuracy of 3 architectural modifications of the network:
Three main models with different architectural modifications were developed. The accuracy and loss of the training and testing of the models are presented. More details about the models are presented in the attached Jupyter notebook.
