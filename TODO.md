* [x] when normalizing the data for `GrowthCOVIDModel` class, the independent variable where the data is measured should also be normalized. This creates additional problems when predicting future growth using `predict` method of `GrowthCOVIDModel` class and when visualizing x-axis in the datetime format using the `initial_growth` function in `coropy.simulate` library.

* [ ] fix the upper bound of confidence interval in SEIR and SEIRD modeling using sensitivity and specificity prediction metrics

* [ ] create tests for the package

* [ ] create docs using Sphinx

* [ ] publish package on PyPi