[![Actions Status](https://github.com/lsils/mockturtle/workflows/Linux%20CI/badge.svg)](https://github.com/lsils/mockturtle/actions)
[![Actions Status](https://github.com/lsils/mockturtle/workflows/MacOS%20CI/badge.svg)](https://github.com/lsils/mockturtle/actions)
[![Actions Status](https://github.com/lsils/mockturtle/workflows/Windows%20CI/badge.svg)](https://github.com/lsils/mockturtle/actions)
[![Coverage Status](https://codecov.io/gh/lsils/mockturtle/branch/master/graph/badge.svg?token=KSC1MP2VCM)](https://codecov.io/gh/lsils/mockturtle)
[![Documentation Status](https://readthedocs.org/projects/mockturtle/badge/?version=latest)](http://mockturtle.readthedocs.io/en/latest/?badge=latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# mockturtle

<img src="https://cdn.jsdelivr.net/gh/lsils/mockturtle@master/mockturtle.svg" width="64" height="64" align="left" style="margin-right: 12pt" />
mockturtle is a C++-17 logic network library.  It provides several logic
network implementations (such as And-inverter graphs, Majority-inverter graphs,
and k-LUT networks), and generic algorithms for logic synthesis and logic
optimization.

[Read the full documentation.](http://mockturtle.readthedocs.io/en/latest/?badge=latest)

## Installation requirements

A modern compiler is required to build *mockturtle*.  We are continously
testing with Clang 12.0.1, GCC 9.3.0, and GCC 10.2.0.  More information can be
found in the [documentation](http://mockturtle.readthedocs.io/en/latest/installation.html).

## EPFL logic sythesis libraries

mockturtle is part of the [EPFL logic synthesis](https://lsi.epfl.ch/page-138455-en.html) libraries.  The other libraries and several examples on how to use and integrate the libraries can be found in the [logic synthesis tool showcase](https://github.com/lsils/lstools-showcase).

## Run experiments

```
makedir build && cd build
cmake -DMOCKTURTLE_EXPERIMENTS=ON ..
make
```
