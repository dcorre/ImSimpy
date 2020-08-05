# Image Simulator for optical/NIR telescope

* Free software: MIT license
* Documentation: https://ImSimpy.readthedocs.io.


Development status
--------------------

[![Build Status](https://travis-ci.com/dcorre/ImSimpy.svg?branch=master)](https://travis-ci.com/dcorre/ImSimpy)
[![codecov](https://codecov.io/gh/dcorre/ImSimpy/branch/master/graphs/badge.svg)](https://codecov.io/gh/dcorre/ImSimpy/branch/master)
[![Documentation Status](https://readthedocs.org/projects/ImSimpy/badge/?version=latest)](https://ImSimpy.readthedocs.io/en/latest/?badge=latest)



Features
--------

* ImSimpy is an Image Simulator for optical/NIR telescope developed in Python3.
* The telescope characteristics are given as input using a hjson file. The telescope performance is first computed with [pyETC](https://github.com/dcorre/pyETC).
* An other hjson file contains the condition of observations: seeing, filter band, exposure time, sky rightness, target elevation for instance but also parameters to compute or load the PSF, to download or load the catalogue, and to control the effects to include in the simulated image (Readout Noise, vignetting,hot and dead pixels, cosmic rays,...).
* The simulated image is aved in a FITS file.


Credits
-------

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter) and the [audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage) project template.
