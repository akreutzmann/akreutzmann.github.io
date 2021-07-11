---
layout: page
title: Examples
---

This page will provide some examples that show how to use the functions provided in emdi. The exampels are sorted by the model class and are also available on [GitHub](https://github.com/akreutzmann/emdi-examples).

## Area-level models

### Basic area-level model 

The basic area-level model was proposed by [Fay and Herriot (1979)](https://www.jstor.org/stable/2286322?seq=1#metadata_info_tab_contents). It requires a direct estimator which could be a total or a mean and its corresponding variance as well as covariate information on the domain level. While the direct estimator bears uncertainty, the covariate information is assumed to be without measurement error. Therefore, registers and administrative data are often used as covariate information. The function provides various estimation approaches for the variance of the random effects and the mean squared error. The following code example will show how to estimate basic area-level estimators and which functions are available for this model class. 

[PDF](https://raw.githubusercontent.com/akreutzmann/emdi-examples/master/area-level-models/basicAreaLevelModel.pdf)

### Transformations: log and arcsin 

Short introduction. 
[PDF](https://raw.githubusercontent.com/akreutzmann/emdi-examples/master/area-level-models/areaLevelTransformations.pdf)
### Spatial correlation 

Short introduction.

[PDF](https://raw.githubusercontent.com/akreutzmann/emdi-examples/master/area-level-models/fhSpatialCorrelation.pdf)

### Robust estimation

Short introduction and PDF.
### Measurement errors

Short introduction and PDF. 

## Unit-level models

### Census EBP approach 
### Data-driven transformations for the EBP 
### EBP under informative sampling 