# wrspathrowData

[![Build Status](https://travis-ci.org/azvoleff/wrspathrowData.png)](https://travis-ci.org/azvoleff/wrspathrowData)

## Overview

The `wrspathrowData` package includes the full Worldwide Reference System (WRS) 
1 and WRS 2 grids used by NASA for cataloging Landsat scenes. The package 
is required by the [`wrspathrow`](http://github.com/azvoleff/wrspathrow) 
package, which contains functions to work with these datasets.

## Package Installation

Note that as `wrspathrowData` contains the full WRS-1 and WRS-2 polygon 
datasets, the package is larger than the average R package (over 26MB when 
installed).  The easiest way to install the development version of the package 
is to download it directly from GitHub (within R) using the 
[`devtools`](http://cran.r-project.org/web/packages/devtools/index.html) package 
by Hadley Wickham. After installing `devtools` from CRAN, type:

```R
install_github('wrspathrowData', username='azvoleff')
```

at the R prompt to install `wrspathrowData`.

## Author Contact Information

[Alex Zvoleff](mailto:azvoleff@conservation.org)  
Postdoctoral Associate  
Tropical Ecology Assessment and Monitoring (TEAM) Network  
Conservation International  
2011 Crystal Dr. Suite 500  
Arlington, VA 22202  
USA
