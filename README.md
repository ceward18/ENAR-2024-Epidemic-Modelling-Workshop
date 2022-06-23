# ISBA 2022 Workshop 

Materials for the ISBA 2022 workshop "Bayesian Modelling of Epidemics: From Population to Individual-level Models"

Presented and created by Dr. Rob Deardon and Dr. Caitlin Ward

## Tentative Schedule

Morning (9:00 - 12:00pm)
Part I: Introduction to Deterministic Epidemics Models
Part II: Population-Averaged Models

Afternoon (1:00pm - 5:00pm)
Part III: Individual-Level Models
Part IV: Analyzing Infectious Disease Data with EpiILM


## Installing Packages

All analyses will be done in R. 

The population-averaged models will be implemented using the R package NIMBLE. Before installing NIMBLE, you need a compiler and related tools such as make that R can use. Detailed instructions to do this are available at https://r-nimble.org/download.

Otherwise, packages used in the workshop can be installed using 

```
install.packages(c('nimble', 'ggplot', 'outbreaks', 'ggforce', 'plyr', 'splines', 'raster', 'sp', 'spdep', 'gganimate', 'EpiILM', 'igraph'))
```

