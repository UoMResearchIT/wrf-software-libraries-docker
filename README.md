# WRF Library docker container

This is a container image for the software libraries needed to build WRF.
It is not designed to be used directly, but instead for use in building other software.


## Requirements

* Docker (version 18.09 or later)

### Container Information

The libraries provided are:
* [zlib](https://github.com/madler/zlib/) v1.2.11
* [libpng](https://download.sourceforge.net/libpng) v1.6.37
* [JasPer](https://github.com/jasper-software/jasper) v2.0.33
* [HDF5](https://github.com/HDFGroup/hdf5) v1.13.1
* [NetCDF-C](https://github.com/Unidata/netcdf-c) v4.8.1
* [NetCDF-fortran](https://github.com/Unidata/netcdf-fortran/) v4.5.4
* [MPICH](https://github.com/pmodels/mpich) v4.0.2


## Pre-built images

Images are available on the GitHub Container Repository:

* [wrf-libraries](https://github.com/UoMResearchIT/wrf-software-libraries-docker/pkgs/container/wrf-libraries).

## Copyright & Licensing

### Libraries

License files for each library are available with the source code. In summary these are:
* zlib: Opensource license
* libpng: PNG Reference Library License version 2
* JasPer: JasPer License Version 2.0
* HDF5: Mixed opensource licenses
* NetCDF: BSD-3-Clause
* MPICH: Opensource license


### Docker scripts

The docker build scripts have been developed by the [Research IT](https://research-it.manchester.ac.uk/) 
department at the [University of Manchester](https://www.manchester.ac.uk/).

Copyright 2023 [University of Manchester, UK](https://www.manchester.ac.uk/).

Licensed under the MIT license, see the LICENSE file for details.