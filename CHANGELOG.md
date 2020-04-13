# Change Log

## 0.4.6
* Added log-base selection in `nominal.conditional_entropy` (issue [#35](https://github.com/shakedzy/dython/issues/35), by **[@ahmedsalhin](https://github.com/ahmedsalhin)**)
* Added new example: `associations_mushrooms_example`
* Renamed example: `associations_example` is now `associations_iris_example`

## 0.4.5
* Requires Python 3.5+
* Private methods and attributes renamed
* Fixed incorrect `__version__` varaible

## 0.4.4
* Minor fixes
* introducing `__all__` to all modules

## 0.4.3
* `binary_roc_graph` is now a private methos, only `roc_graph` is exposed

## 0.4.2
* Added new functionality to `model_utils.roc_graph` (Plot best threshold, print class names)

## 0.4.1
* Added `nominal.cluster_correlations`, and an option to cluster `nominal.associations` heatmap (by **[@benman1](https://github.com/benman1)**)

## 0.4.0
* Added automatic recognition of categorical columns in `nominal.associations` (by **[@benman1](https://github.com/benman1)**)

## 0.3.1
* `nominal.associations` can accept an exisiting Matplotlib `Axe` (issue [#24](https://github.com/shakedzy/dython/issues/24), by **[@Baukebrenninkmeijer](https://github.com/Baukebrenninkmeijer)**)

## 0.3.0
* Introducing missing values handeling (`nan_strategy`) in `nominal` module (issue [#15](https://github.com/shakedzy/dython/issues/15))

## 0.2.0
* Added `sampling` module

## 0.1.1
* Fixed missing `sqrt` in `nominal.correlation_ratio` (issue [#7](https://github.com/shakedzy/dython/issues/7))

## 0.1.0
* First version of Dython