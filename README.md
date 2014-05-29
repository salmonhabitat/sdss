![](http://img.shields.io/badge/version-alpha-red.svg?style=flat)

__Atlantic salmon spatial decision support system__

The Atlantic salmon spatial decision support system _(ASDSS)_ identifies and prioritizes actions that are most likely to ameliorate threats to Atlantic salmon populations in Downeast Maine. 

![](https://raw.githubusercontent.com/salmonhabitat/sdss/master/ats.jpg)

## Overview

The Desert Tortoise SDSS model we based the ATS version off of consists of the 10 following components:

1. Spatial Threats
2. Threat-Stress Interaction Model
3. Relative Stress Model
4. Demographic Impact Model
5. Single Risk/Threat Model
6. Pre-action Aggregate Risk Model
7. Recovery Action Effectiveness Model
8. Recovery Action Risk Reduction Model
9. Post-action Aggregate Risk Model
10. Spatial Summary/Prioritization

For the first stage of the ATSDSS model, we focused on developing models 1-3.

### 1. Spatial Threats

> Utilizes spatial data to represent where threats occur geographically.

Spatial data was gathered from a variety of sources, including the MEGIS Data Portal. Because we narrowed the scope of the model to the Downeast SHRU, many of the threats that may affect ATS in urban settings did not apply, and thus simplified the data collection efforts.

### 2. Threat-Stress Interaction Model

> Estimates the contribution of each threat to stress the population.

The University of Redlands had previously developed a [Model Manager](http://www.spatial.redlands.edu/dtro/modelmanager/) which we were able to use here. The application provides a means of describe the relationships between threats and stresses. Using the spatial data we gathered, a network was developed, and weights assigned.

### 3. Relative Stress Model

> Estimates the contribution of each stress to overall population change.

Again, the Model Manager was used for this portion of the project. Weights and relationships were assigned based off of previous work that is available in the documentation.

## Next steps

The weights for the various threat/stress relationships were developed based on previous work and estimates. They do not reflect the priorities of the managers and invested parties that currently exist. Getting their feedback regarding weights is an important next step in developing this into an effective management tool.

## Changelog

- _v0.1.0_ Initial import.
