# Wildfire Risk Prediction
---

*In collaboration with [Natasha Stavros](https://earthlab.colorado.edu/our-team/natasha-stavros) and [Max Cook](https://earthlab.colorado.edu/our-team/max-cook).* 

- [Leader Board](#Leader-Board)
- [Problem Statement](#Background)
- [Goal](#Goal)
- [Data](#Data)
- [Reference](#Reference)

## Leader Board

Team Name | RMSE (Structure Damaged) | Mean Error (Structure Damaged) | Median Error (Structure Damaged)| RMSE (Structure Destroyed) | Mean Error (Structure Destroyed) | Median Error (Structure Destroyed)  
--------- | ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ 
SEEKingTreesOnFire  | 698.3  | -47.5 | -0.1 | 691.0 | -32.4 | 0.5
Firefly | 712.7 | -50.2 | 0.4 | 734.6 | -44.6 | 1.1
too_hot_to_handle | 712.5 | -50.1 | 0.4 | 734.6 | -44.1 | 1.1
Into the Wild | 705.4 | -48.7 | 0.2 | 726.8 | -42.0 | 4.6

## Background

The increasing frequency and intensity of wildfire events are threatening the natural and human systems in the western part of the United States. In 
the past few decades, wildfire burned areas in the western U.S. have at least tripled (Balch et al., 2018). This increase is strongly influenced by 
climate change (Stavros et al., 2014). These wildfire events caused significant economic loss to society and threatened the safety of the local community.
The risk of a community to dangerous wildfire events is a combination of climatic conditions, topography, vegetation/fuels, and local development patterns.
It is critical for us to understand wildfire risk in a complex human-natural system using innovative methods and linked environmental and socioeconomic data.

## Goal

The goal of this hackathon is to develop a data-driven method to predict the risk of the local community to wildfire using climatic, local development, 
and topography data. The historical damaged and destroyed structures/buildings from wildfire incidents reports (2000–2014) are used as the proxy to quantify
the risk of wildfire for local communities. The developed model will be evaluated using 2015–2018 data where the wildfire damage will be held unknown to 
participants.

## Data

Information about data used in this hackathon, please visit the [Problem Statement](https://docs.google.com/document/d/1Gw14-58lSSemVnsBf576OIHvBuUZTU-0EeQXbPbaIhc/edit#).

- [Training Data for 2000-2014](https://drive.google.com/drive/u/2/folders/1koJ8iV0Hd3r6zINmY5zP-hCaoLMTUWfy)
- [Testing Data for 2015-2018](https://drive.google.com/drive/u/2/folders/1OxFKKNcw-Gv0NNwscLSLnHy1HVZ05oz8)

## Reference

- Stavros, E.N., Abatzoglou, J.T., McKenzie, D., et al. Regional projections of the likelihood of very large wildland fires under a changing climate in the contiguous Western United States. Climatic Change 126, 455–468 (2014). https://doi.org/10.1007/s10584-014-1229-6
- Balch, J.K., Schoennagel, T., Williams, A.P., Abatzoglou, J.T., Cattau, M.E., Mietkiewicz, N.P., & St Denis, L.A. (2018). Switching on the big burn of 2017. Fire, 1(1), 17. https://doi.org/10.3390/fire1010017 
- St. Denis, L.A., Mietkiewicz, N.P., Short, K.C. et al. All-hazards dataset mined from the US National Incident Management System 1999–2014. Sci Data 7, 64 (2020). https://doi.org/10.1038/s41597-020-0403-0
- Balch, J.K., St. Denis, L.A., Mahood, A.L., Mietkiewicz, N.P., Williams, T.M., McGlinchy, J., Cook, M.C.. FIRED (Fire Events Delineation): An Open, Flexible Algorithm and Database of US Fire Events Derived from the MODIS Burned Area Product (2001–2019). Remote Sensing. 2020; 12(21):3498. https://doi.org/10.3390/rs12213498 
- Uhl, J.H., Leyk, S., McShane, C.M., Braswell, A.E., Connor, D.S., & Balk, D. 2021. Fine-grained, spatiotemporal datasets measuring 200 years of land development in the United States, Earth Syst. Sci. Data, 13, 119–153, https://doi.org/10.5194/essd-13-119-2021.
- Abatzoglou, J.T., & Williams, A.P. (2016). Impact of anthropogenic climate change on wildfire across western US forests. Proceedings of the National Academy of Sciences, 113(42), 11770-11775. https://doi.org/10.1073/pnas.1607171113
- Holsinger, L., Parks, S.A., & Miller, C. (2016). Weather, fuels, and topography impede wildland fire spread in western US landscapes. Forest ecology and management, 380, 59-69. https://doi.org/10.1016/j.foreco.2016.08.035

## Acknowledgement

This hackathon topic is developed in collaboration with Natasha Stavros and Maxwell Cook at the University of Colorado, Boulder. The linked database ICS-FIRED
is provided by Maxwell Cook, which is in the process of being published. If you plan to expand the hackathon work into future research, please discuss 
with [Max Cook](mailto:maxwell.cook@colorado.edu) and [Natasha Stavros](mailto:Natasha.Stavros@colorado.edu) for updated data information.
