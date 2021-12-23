# How thick is it anyway?
## Predict key property using ensemble machine learning

## Objective
Applied supervised machine learning techniques to predict the apparent viscosity of nanoparticle stabilized CO2 foam for hydraulic fracturing. Blending, a variant of stacking ensemble learning technique explored as alternative for expensive laboratory experiments. Also, determine the influence of various parameters on apparent viscosity prediction.

## The Dataset
45 input data points were compiled from the published results of Fu and Liu's (2021) laboratory rheology experiments on nanoparticle-stabilized CO2-foam at high temperatures and pressure.
The authors varied the temperature, concentration of nanoparticles, salinity, quality of foam, and the shear rate at constant backpressure of 1,300 psi. These variables served as input features for this analysis to predict the apparent viscosity of NP-CO2-foam when used as fracturing fluid.
217 additional data records were generated from the collected dataset by polynomial interpolation to make a total of 262 records.

## Key Skills Demonstrated
* Ensemble learning technique
* Significant feature identification using PCA and Permutation Feature importance
* Model tuning and evaluation
* Model comparison

## Publication
This is the code for generating the analysis and plots for the best performing model (SVR-based meta-model ensembled with blending, a variant of stacking approach) for the following manuscript:
> Olukoga, T. A., & Feng, Y. (2021). Ensemble machine learning for predicting nanoparticle stabilized CO2 foam rheology in unconventional reservoir fracturing. Under review with 
SPE Reservoir evaluation and Engineering
