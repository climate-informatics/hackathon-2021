# ClimateBench
---

*In collaboration with [Duncan Watson-Parris](https://duncanwp.github.io/).* 

- [Scoring Board](#Scoring-Board)
- [Problem Statement](#Background)
- [Goal](#Goal)

## Scoring Board (Updated every 6 hours)  

--

## Background
Many different emissions pathways exist that are compatible with the Paris climate agreement, and many more are possible that miss that target. Sampling possible emissions scenarios are therefore crucial for policymakers to weigh the cost and impact of different mitigation and adaptation strategies. While many of the most complex Earth System Models have simulated a small selection of ‘Shared Socioeconomic Pathways’ it is impractical to use these expensive models to fully explore the space of possibilities. Therefore such explorations mostly rely on one-dimensional impulse response models, or simple pattern scaling approaches to approximate the physical climate response to a given scenario. 

Impulse response models are physically interpretable and can capture non-linear behavior, but are inherently unable to model regional climate changes, while the pattern scaling approaches rely on a simple scaling of spatial distributions of e.g. precipitation by global mean temperature changes, neglecting strong non-linearities in these relationships. Statistical emulators of the regional climate have been developed although these have been quite bespoke (e.g., Castruccio et al., 2014) or focus on the relatively simple problem of emulating temperature. Recent approaches including non-linear pattern scaling (Beusch et al., 2020) and GP emulation of long-term climate responses (Mansfield et al., 2020) hint at the possibility of using modern machine learning tools to produce robust and general emulators over future scenarios.

--

## Goal

This challenge sets out to create a benchmark dataset and set of models similar to WeatherBench (Rasp et al., 2020) but for the climate community. The aim is to predict annual mean global distributions of temperature and precipitation given emissions and concentrations of key anthropogenic climate forcing: SO2, BC, CH4, and CO2. (This predicts the fast response to these drivers which we assume to be the most policy-relevant, particularly for high-ambition targets.) 


