
# R-micromap-package-development

CRAN: [![Downloads from the RStudio CRAN mirror](http://cranlogs.r-pkg.org/badges/grand-total/micromap)](http://cran.rstudio.com/package=micromap)

Linux: [![Travis-CI Build Status](https://travis-ci.org/fawda123/R-micromap-package-development.svg?branch=master)](https://travis-ci.org/fawda123/R-micromap-package-development)

Windows: [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/fawda123/R-micromap-package-development?branch=master)](https://ci.appveyor.com/project/fawda123/R-micromap-package-development)

This repository is for development of the USEPA R micromap package.   If you would like to contribute to this repository please follow the guidelines in [CONTRIBUTING](CONTRIBUTING.md).

### Installing the package

Version 1.9.2 is the stable version on CRAN and can be installed as follows.


```r
# install from CRAN
install.packages('micromap')
library(micromap)
```

The development version can be installed from the development branch on the repository.


```r
# requires devools to install
install.packages('devtools')
library(devtools)

# install from repo
install_github('USEPA/R-micromap-package-development', ref = 'development')
library(micromap)
```

### Citation


```r
citation(package = 'micromap')
```

```
## 
## To cite the micromap package in publications use:
## 
##   Quinn C. Payton, Michael G. McManus, Marc H. Weber, Anthony R.
##   Olsen, and Thomas M. Kincaid (2015). micromap: A Package for
##   Linked Micromaps. Journal of Statistical Software, 63(2), 1-16.
##   URL http://www.jstatsoft.org/v63/i02/.
## 
## A BibTeX entry for LaTeX users is
## 
##   @Article{,
##     title = {{micromap}: A Package for Linked Micromaps},
##     author = {Quinn C. Payton and Michael G. McManus and Marc H. Weber and Anthony R. Olsen and Thomas M. Kincaid},
##     journal = {Journal of Statistical Software},
##     year = {2015},
##     volume = {63},
##     number = {2},
##     pages = {1--16},
##     url = {http://www.jstatsoft.org/v63/i02/},
##   }
```

### Using the functions

A detailed overview of the micromap package is provided as in introduction guide that is included with the package.  Additional information can be found from the [publication](http://www.jstatsoft.org/v63/i02/) in the Journal of Statistical Software. 

### EPA Disclaimer

The United States Environmental Protection Agency (EPA) GitHub project code is provided on an "as is" basis and the user assumes responsibility for its use. EPA has relinquished control of the information and no longer has responsibility to protect the integrity , confidentiality, or availability of the information. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recomendation or favoring by EPA. The EPA seal and logo shall not be used in any manner to imply endorsement of any commercial product or activity by EPA or the United States Government.

By submitting a pull request, you make an agreement with EPA that you will not submit a claim of compensation for services rendered to EPA or any other federal agency.  Further, you agree not to charge the time you spend developing software code related to this project to any federal grant or cooperative agreement.

### License

This project is licensed under the GNU General Public License, [GPL-2](http://cran.r-project.org/web/licenses/GPL-2).  
