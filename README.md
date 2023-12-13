# Santa Barbara Land Cover Classification

## Overview
This repository contains rmarkdown code and rproject directory for a land cover analysis project focused on southern Santa Barbara County. The project utilizes remote sensing techniques, specifically a supervised approach using a decision tree classifier, to classify land cover types based on multi-spectral imagery.

## Background
Remote sensing offers a valuable capability to distinguish various materials based on their spectral reflectance, enabling the identification of land cover types across extensive regions. This categorization is crucial for understanding the spatial distribution and dynamics of land cover, providing valuable insights into the effects of changing environmental conditions, especially under the influence of climate change.

In this analysis, we employ a supervised approach, specifically utilizing a decision tree classifier, to assess land cover in southern Santa Barbara County. The decision tree classifier relies on a training dataset containing information on both the land cover classification and the spectral properties of each pixel. By establishing conditions based on these attributes during training, the decision tree becomes capable of characterizing different land cover types. When applied to a new spectral image, the trained decision tree can effectively identify the land cover type for individual pixels1.

As residents of Santa Barbara, California, our goal is to leverage multi-spectral imagery and location data to determine the prevalent land cover types in southern Santa Barbara County. The primary land cover categories of interest include green vegetation, dry grass or soil, urban areas, and water bodies.

## Data
The data used in this analysis is derived from landsat 5 and polygons of sourthern SB county that contain training data. The data folder was included in gitignore, but the raw data was uploaded to this repository in the "data" folder.

## Credit
The project is based on materials developed by Chris Kibler, and was restructed by Ruth Oliver at UC Santa Barbara.
