![PyHELP](./images/pyhelp_banner_v2.png)

[![license](https://img.shields.io/pypi/l/pyhelp.svg)](./LICENSE)
[![Latest release](https://img.shields.io/github/release/cgq-qgc/pyhelp.svg)](https://github.com/cgq-qgc/pyhelp/releases)
[![Documentation Status](https://readthedocs.org/projects/pyhelp/badge/?version=latest)](http://pyhelp.readthedocs.io)
[![Build status](https://ci.appveyor.com/api/projects/status/ns6s8x0hkd31ffb3/branch/master?svg=true)](https://ci.appveyor.com/project/jnsebgosselin/pyhelp-rd625/branch/master)
[![codecov](https://codecov.io/gh/cgq-qgc/pyhelp/branch/master/graph/badge.svg)](https://codecov.io/gh/cgq-qgc/pyhelp)

PyHELP is an object oriented Python library providing a set of tools to
estimate spatially distributed groundwater recharge and other hydrological
components (runoff and evapotranspiration) using the HELP
([Hydrologic Evaluation of Landfill Performance](https://www.epa.gov/land-research/hydrologic-evaluation-landfill-performance-help-model))
model.
PyHELP integrates weather data (from grids or stations), land conditions
defined by a series of GIS maps as well as soil and geological material
properties into HELP input files.
PyHELP also processes HELP simulation results and outputs them as
maps and graphs, including comparisons of simulation results with
stream hydrographs.
PyHELP thus accompanies users through the entire workflow from input file
assembly to model calibration and to the documentation of results.
This workflow is based on the method originally developed by
[Croteau et al. (2011)](https://www.tandfonline.com/doi/abs/10.4296/cwrj3504451)
to assess spatially distributed groundwater recharge at the regional scale.

Please consult the [documentation](http://pyhelp.readthedocs.io) for more
details or contact us at [jean-sebastien.gosselin@ete.inrs.ca](mailto:jean-sebastien.gosselin@ete.inrs.ca).

## Install

Pip Wheels and Conda packages are both available for Python 3.7 and 3.8 on the Windows 64bits plateform. If you need to use PyHELP with a version of Python other than 3.7 or 3.8, or if you are working on Linux or macOS, you will have to build and install PyHELP from source. Please visit our [documentation](https://pyhelp.readthedocs.io/en/latest/installation.html) for more details.

[![Anaconda-Server Badge](https://anaconda.org/cgq-qgc/pyhelp/badges/installer/conda.svg)](https://anaconda.org/cgq-qgc/pyhelp)

The easiest method to install a released version of PyHELP on Windows is with [Conda](https://conda.io/docs/index.html). To do so, you will need first to download and install the [Anaconda distribution](https://www.anaconda.com/distribution/) on your computer. Anaconda comes with the most important Python scientific libraries (i.e. Numpy, Pandas, Matplotlib, IPython, etc), including all PyHELP dependencies, in a single, easy to use environment.

Then, PyHELP can be installed, along with all its dependencies, by executing the following command in a terminal:

`conda install -c cgq-qgc pyhelp`

When a new released version of PyHELP is made available on the [Anaconda cgq-qgc channel](https://anaconda.org/cgq-qgc/pyhelp), PyHELP can be updated by executing the following command in a terminal:

`conda update -c cgq-qgc pyhelp`

[![Anaconda-Server Badge](https://anaconda.org/cgq-qgc/pyhelp/badges/installer/pypi.svg)](https://pypi.org/project/pyhelp/)

It is also possible to install PyHELP with [pip](https://pypi.org/project/pip/), but be aware that pip installations are for advanced users.

First, you will need to download and install either Python 3.7 or 3.8 on your computer.

Then, you will be able to install PyHELP with pip, along with all its dependencies, by executing the following command in a terminal:

`python -m pip install pyhelp`
