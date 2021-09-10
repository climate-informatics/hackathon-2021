# ClimateBench

*In collaboration with [Duncan Watson-Parris](https://duncanwp.github.io/).* 

- [Scoring Board](#Scoring-Board)
- [Problem Statement](#Background)
- [Goal](#Goal)
- [Data](#Data)
- [Reference](#Reference)

## Scoring Board (Updated every 6 hours)  

Team Name | RMSE (Ta) | RMSE (DTR) | RMSE (Prcp) | RMSE (Prcp_90) 
--------- | --------- | ---------- | ----------- | --------------
  |   |   |   | 

## Background
Many different emissions pathways exist that are compatible with the Paris climate agreement, and many more are possible that miss that target. Sampling possible emissions scenarios are therefore crucial for policymakers to weigh the cost and impact of different mitigation and adaptation strategies. While many of the most complex Earth System Models have simulated a small selection of ‘Shared Socioeconomic Pathways’ it is impractical to use these expensive models to fully explore the space of possibilities. Therefore such explorations mostly rely on one-dimensional impulse response models, or simple pattern scaling approaches to approximate the physical climate response to a given scenario. 

Impulse response models are physically interpretable and can capture non-linear behavior, but are inherently unable to model regional climate changes, while the pattern scaling approaches rely on a simple scaling of spatial distributions of e.g. precipitation by global mean temperature changes, neglecting strong non-linearities in these relationships. Statistical emulators of the regional climate have been developed although these have been quite bespoke (e.g., Castruccio et al., 2014) or focus on the relatively simple problem of emulating temperature. Recent approaches including non-linear pattern scaling (Beusch et al., 2020) and GP emulation of long-term climate responses (Mansfield et al., 2020) hint at the possibility of using modern machine learning tools to produce robust and general emulators over future scenarios.


## Goal

This challenge sets out to create a benchmark dataset and set of models similar to WeatherBench (Rasp et al., 2020) but for the climate community. The aim is to predict annual mean global distributions of temperature and precipitation given emissions and concentrations of key anthropogenic climate forcing: SO2, BC, CH4, and CO2. (This predicts the fast response to these drivers which we assume to be the most policy-relevant, particularly for high-ambition targets.) 

## Data

ClimateBench is a benchmark dataset for climate model emulation inspired by [WeatherBench](https://github.com/pangeo-data/WeatherBench). It consists of NorESM2 simulation outputs with associated forcing data processed in to a consistent format from a variety of experiments performed for CMIP6. Multiple ensemble members are included where available.

The processed training and validation data can be obtained from Zenodo: [10.5281/zenodo.5196512](https://doi.org/10.5281/zenodo.5196512).

- [Training Data](https://doi.org/10.5281/zenodo.5465895)
- [Testing Data](https://drive.google.com/drive/u/2/folders/1VjoGpQjQxoruq5qCj90Txnz--ss5ulvg)

## Reference

- Castruccio, S., McInerney, D. J., Stein, M. L., Liu Crouch, F., Jacob, R. L., & Moyer, E. J. (2014). Statistical emulation of climate model projections based on precomputed GCM runs. Journal of Climate, 27(5), 1829-1844. https://doi.org/10.1175/JCLI-D-13-00099.1 
- Beusch, L., Gudmundsson, L., & Seneviratne, S. I. (2020). Emulating Earth system model temperatures with MESMER: from global mean temperature trajectories to grid-point-level realizations on land. Earth System Dynamics, 11(1), 139-159. https://doi.org/10.5194/esd-11-139-2020
- Mansfield, L.A., Nowack, P.J., Kasoar, M. et al. Predicting global patterns of long-term climate change from short-term simulations using machine learning. npj Clim Atmos Sci 3, 44 (2020). https://doi.org/10.1038/s41612-020-00148-5
- Rasp, S., Dueben, P. D., Scher, S., Weyn, J. A., Mouatadid, S., & Thuerey, N. (2020). WeatherBench: a benchmark data set for data‐driven weather forecasting. Journal of Advances in Modeling Earth Systems, 12(11), e2020MS002203. https://doi.org/10.1029/2020MS002203
- Seland, Ø., Bentsen, M., Olivié, D., Toniazzo, T., Gjermundsen, A., Graff, L. S., ... & Schulz, M. (2020). Overview of the Norwegian Earth System Model (NorESM2) and key climate response of CMIP6 DECK, historical, and scenario simulations. Geoscientific Model Development, 13(12), 6165-6200. https://doi.org/10.5194/gmd-13-6165-2020 

