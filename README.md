# RStudio with bioinformatics package GWASCAT that runs served via Binder 

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/fomightez/binderized-gwascat/master)

This deploys a Binder that exposes the
RStudio UI instead of a Jupyter Notebook. It also installs
the gwascat bioinformatics package and adds a script
based on Vince Buffalo's [Using Bioconductor to Analyze your 23andme Data](http://www.vincebuffalo.com/blog/2012/03/12/using-bioconductor-to-analyze-your-23andme-data.html) updated to run in a relatively current R/RStudio/Bioconductor environment.

Running RStudio session
-----------------------

To start your RStudio session once [the Binder server](http://mybinder.org/v2/gh/fomightez/dockerfile-rstudio/master) has launched and you are greeted with the Jupyter dashboard, click on "New" in the top right,
and at the bottom will be `RStudio Session`.
Click that and your RStudio session will begin momentarily!

See `instructions.ipynb` for more details.


Details for the curious
--------------------

The provenance of this repository...  
The contents for this repository were copied from my repo [binderized-dockerfile-rstudio](https://github.com/fomightez/binderized-dockerfile-rstudio) and the `gwascat` package was added along with an updated version of the commands from Vince Buffalo's [Using Bioconductor to Analyze your 23andme Data](http://www.vincebuffalo.com/blog/2012/03/12/using-bioconductor-to-analyze-your-23andme-data.html).
See my repo [binderized-dockerfile-rstudio](https://github.com/fomightez/binderized-dockerfile-rstudio) for details on how I made that repo from [a repo set up as an example for RStudio in Binder using a Dockerfile](https://github.com/binder-examples/dockerfile-rstudio).

