I strive for open science and open source software in particular.
I like  contributing to software that I use regularly (that's my way of
thanking) and creating my own software.
Here you can find some highlights of my contributions on GitHub.
For an exhaustive list, you can check out my
[GitHub profile](https://github.com/johannfaouzi).

## Personal software

### pyts: [GitHub](https://github.com/johannfaouzi/pyts), [Documentation](https://pyts.readthedocs.io)

I created and maintain [pyts](https://github.com/johannfaouzi/pyts),
which is a Python package dedicated to time series classification.
It aims to make time series classification easily accessible by providing
preprocessing tools, dataset loading utilities and implementations of many
algorithms.


## Other software

### scikit-learn: [GitHub](https://github.com/scikit-learn/scikit-learn), [Documentation](https://scikit-learn.org)

* [PR #14999](https://github.com/scikit-learn/scikit-learn/pull/14999): I changed
the use of the random seeds in
[sklearn.ensemble.HistGradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingClassifier.html)
and
[sklearn.ensemble.HistGradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html),
so that the same seed is used when warm starting is used (this way, the training
and validation sets are always identical, which prevents data leakage).

* [PR #14516](https://github.com/scikit-learn/scikit-learn/pull/14516): I changed
the default behavior for early stopping
[sklearn.ensemble.HistGradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingClassifier.html)
and
[sklearn.ensemble.HistGradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html),
which is now 'auto': by default, early stopping is enabled if there are at least
10,000 samples.

* [PR #14012](https://github.com/scikit-learn/scikit-learn/pull/14012): I added
a `warm_start` parameter to
[sklearn.ensemble.HistGradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingClassifier.html)
and
[sklearn.ensemble.HistGradientBoostingRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html),
allowing users to reuse the solution of the previous call to fit and add more
estimators to the ensemble.

* Typo fixes:
[PR #13932](https://github.com/scikit-learn/scikit-learn/pull/13932),
[PR #14072](https://github.com/scikit-learn/scikit-learn/pull/14072),
[PR #14073](https://github.com/scikit-learn/scikit-learn/pull/14073),
[PR #14130](https://github.com/scikit-learn/scikit-learn/pull/14130),
[PR #14245](https://github.com/scikit-learn/scikit-learn/pull/14245),
[PR #15280](https://github.com/scikit-learn/scikit-learn/pull/15280),
[PR #16106](https://github.com/scikit-learn/scikit-learn/pull/16106),
[PR #16379](https://github.com/scikit-learn/scikit-learn/pull/16379).

* Maintenance stuff:
[PR #14194](https://github.com/scikit-learn/scikit-learn/pull/14194),
[PR #14074](https://github.com/scikit-learn/scikit-learn/pull/14074).


### tslearn: [GitHub](https://github.com/rtavenar/tslearn) - [Documentation](https://tslearn.readthedocs.io)

* [PR #104](https://github.com/rtavenar/tslearn/pull/104): I updated the functions
to compute Dynamic Time Warping and the constraint regions, replacing the
Cython functions with numba functions.

* Maintenance stuff:
[PR #135](https://github.com/rtavenar/tslearn/pull/135),
[PR #119](https://github.com/rtavenar/tslearn/pull/119).


### numpy: [GitHub](https://github.com/numpy/numpy) - [Documentation](https://numpy.org)

* Typo fixes:
[PR #14035](https://github.com/numpy/numpy/pull/14035),
[PR #13947](https://github.com/numpy/numpy/pull/13947).


### scipy: [GitHub](https://github.com/scipy/scipy) - [Documentation](https://scipy.org/scipylib/)

* [PR #10435](https://github.com/scipy/scipy/pull/10435): I fixed a bug which
prevented the use of the
[Yeo-Johnson transformation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.yeojohnson.html)
for integer data type.

* Typo fixes:
[PR #9570](https://github.com/scipy/scipy/pull/9570).


### umap: [GitHub](https://github.com/lmcinnes/umap) - [Documentation](https://umap-learn.readthedocs.io)

* [PR #130](https://github.com/lmcinnes/umap/pull/130): I added an example
illustrating the use of the
[UMAP](https://umap-learn.readthedocs.io/en/latest/api.html#umap) class with
[sklearn.pipeline.Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)

* Typo fixes:
[PR #120](https://github.com/lmcinnes/umap/pull/120),
[PR #118](https://github.com/lmcinnes/umap/pull/118),
[PR #109](https://github.com/lmcinnes/umap/pull/109).
