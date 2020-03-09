I strive for open science and open source software in particular.
I like  contributing to software that I use regularly (that's my way of
thanking) and creating my own software.
Here you can find some highlights of my contributions on GitHub.
For an exhaustive list, you can check my
[GitHub profile](https://github.com/johannfaouzi).

## Personal software

* I created and maintain [pyts](https://github.com/johannfaouzi/pyts),
which is a Python package dedicated to time series classification.
It aims to make time series classification easily accessible by providing
preprocessing tools, dataset loading utilities and implementations of many
algorithms.

## Other software

### scikit-learn

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

* Fixing typos:
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


### tslearn



### numpy



### scipy

### umap-learn
