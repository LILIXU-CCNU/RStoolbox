Patch release: fixes tests for upcoming raster version. 

### R CMD checks
### Test environments
* Ubuntu 16.10 64bit (release)
* Travis-CI Ubuntu 14.04 (devel)
* winbuilder (devel, release, oldrel)
* r-hub (devel+ubsan)

### R CMD check results
There were no ERRORs or WARNINGs. 

There was 1 NOTE:
Possibly mis-spelled words in DESCRIPTION:
  indices (10:26)

This is a false alarm; 'indices' is spelled correctly.  

### Downstream dependencies
none

### Changelog RStoolbox 0.1.10
Fixes:
* adapt to upcoming raster version
