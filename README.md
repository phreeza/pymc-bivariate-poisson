# pymc-bivariate-poisson
A Stochastic class implementing the bivariate Poisson process for [PyMC 2](http://pymc-devs.github.io/pymc/).

Useful for the modeling of sports scores, in particular sports in which the score depends on the pace of the match such as basketball.

## Installation
[Cython](http://cython.org/) is required to build this module.

To compile the Cython submodule, run the following command:
```
python setup.py build_ext --inplace
```
