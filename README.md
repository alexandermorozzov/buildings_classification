# OSM Buildings Classification

## Notebooks: 

- [vo_test.ipynb](https://github.com/alexandermorozzov/buildings_classification/blob/main/vo_test.ipynb) – preprocess data for `DecisionTreeClassifier` training (it is necessary to have ground-truth data);
- [merging_gdfs_for_fit.ipynb](https://github.com/alexandermorozzov/buildings_classification/blob/main/merging_gdfs_for_fit.ipynb) - merging all GeoDataFrames for model fittng and further training;
- [tashkent.ipynb](https://github.com/alexandermorozzov/buildings_classification/blob/main/tashkent.ipynb) - preprocess data for Toshkent city (Uzbekistan) and prediction of residential/non-residential type of buildings.

## Reference

This repository was forked from [osm_buildings_classifictaion](https://github.com/heykuldip/osm_buildings_classification) to apply the prediction method on new data. Publication reference:  

- [Atwal, K.S., Anderson, T., Pfoser, D. et al. Predicting building types using OpenStreetMap. Sci Rep 12, 19976 (2022).](https://doi.org/10.1038/s41598-022-24263-w)