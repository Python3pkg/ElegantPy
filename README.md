# ElegantPy
Provides a Python wrapper for Elegant to make analysis (much!) simpler

## Purpose

Elegant is a simulation tool developed at ANL:

http://www.aps.anl.gov/Accelerator_Systems_Division/Accelerator_Operations_Physics/software.shtml#elegant

It is a particle-tracking code. Unfortunately, the code for accessing its data is out of date. Using the Python packages offered by ANL is cumbersome, using old-style classes, and the packages are split in two. This package acts as a wrapper for accessing data, combining the two packages and providing an interface that is easier to use by providing methods and attributes for common tasks.

## Future Plans

* Create Elegant configuration files within Python
* Write Elegant bunch files for loading and simulation
