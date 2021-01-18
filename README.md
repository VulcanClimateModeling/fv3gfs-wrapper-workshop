# fv3gfs-wrapper workshop

Materials for the workshop held for GFDL in January 2021.

## Cloning the and entering the repository

To clone and enter the repository run:

```
$ git clone https://github.com/VulcanClimateModeling/fv3gfs-wrapper-workshop.git
$ cd fv3gfs-wrapper-workshop
```

## Downloading the reference data

The run directory that the examples in this workshop will be based on can be
found on [Zenodo](https://zenodo.org/record/4429298#.YAWs5i1h1qs).  To download
the run directory and put in a place most easily accessible from the notebooks,
run the following from the root level of the repository:

```
$ wget https://zenodo.org/record/4429298/files/c48_6h.tar.gz?download=1
$ tar -xzvf c48_6h.tar.gz?download=1
$ mv rundir examples/notebooks/reference_rundir
```

If you have already downloaded the reference data, move or copy it to a directory
named `examples/notebooks/reference_rundir`.

## Setup for running notebooks

From within the repository navigate to the `examples` directory and run `make all`:

```
$ cd examples
$ make all
```

## Other useful links

### GitHub repositories

- [fv3gfs-wrapper](https://github.com/VulcanClimateModeling/fv3gfs-wrapper): the source code for the Python wrapper
- [fv3gfs-fortran](https://github.com/VulcanClimateModeling/fv3gfs-fortran): the fortran source code for Vulcan's fork of FV3GFS
- [fv3gfs-util](https://github.com/VulcanClimateModeling/fv3gfs-util): the source code for tools used by the Python wrapper
  
### Documentation

- [fv3gfs-wrapper](https://vulcanclimatemodeling.github.io/fv3gfs-wrapper/index.html)
- [fv3gfs-util](https://fv3gfs-util.readthedocs.io/en/latest/index.html)
