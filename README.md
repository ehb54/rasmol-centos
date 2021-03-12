# rasmol-centos

## Background 
Had trouble getting a version of [RasMol](http://rasmol.org) to work under CentoOS.

This is needed by [US-SOMO](https://somo.aucsolutions.com).

This is a copy of the RasMol 2.7.5.2 binary I had on an Ubuntu 16.04 system along with the missing libraries.

## Usage

Install, make sure lib/ is in your LD_LIBRARY_PATH and run bin/rasmol


## Notes

 - If you have issues or find further missing libraries, please create an issue here.
 - If you already have some of the libraries, you may not need everything in lib
 - Missing libraries can be identified by ```ldd rasmol | grep 'not found'```
 - demo/1HEL.pdb is a copy downloaded from the [RCSB](https://www.rcsb.org/)
