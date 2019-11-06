# Singapore Pools Analysis
Analysis of Winning Statistics of Singapore Pools

# Getting Started
## Prerequisites
This project uses jupyter notebook, see [here](https://jupyter.readthedocs.io/en/latest/install.html) for installation.

The following libraries are used for this notebook (installed via [anaconda](https://www.anaconda.com/distribution/)):
* beautifulsoup4
* numpy
* pandas
* matplotlib
* sklearn
* lightgbm

# Analysis:
* 4D Winning Numbers
* Toto Winning Numbers
* Toto Outlets

# TODO:
* Plot geoloc info in `basemap`
  * Reference:
    * Onemap (Limited Functionality) - https://docs.onemap.sg/#search
    * Geocoding - https://developers.google.com/maps/documentation/geocoding/intro
  * Geocoding API Endpoint - https://maps.googleapis.com/maps/api/geocode/json?address=[**url encoded address**]&key=**YOUR_API_KEY**
  * Might checkout `geopandas` too

# References
* 4D Results - http://www.singaporepools.com.sg/en/product/Pages/4d_results.aspx
* Toto Results - http://www.singaporepools.com.sg/en/product/Pages/toto_results.aspx
