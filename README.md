# wrf-docker

This build system creates the library docker container for WRF / WPS.

Main page: https://github.com/wrf-model/WRF

## Requirements

* Docker (version 18.09 or later)

## Pre-built images

Images are hosted via github packages:

* [library](https://github.com/UoMResearchIT/wrf-docker/pkgs/container/wrf-libraries) container

## Provided libraries

* zlib
* libpng
* JasPer
* HDF5
* NetCDF
* MPICH

## Usage

To build a specific target in the base container use `--target <target name>`, e.g.:
* `DOCKER_BUILDKIT=1 docker build . --target final -t 'wrf_build_test' -f Dockerfile-base`

