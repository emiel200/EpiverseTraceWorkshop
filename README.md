
<!-- README.md is generated from README.Rmd. Please edit that file -->

# EpiverseTraceWorkshop

<!-- badges: start -->
<!-- badges: end -->

Research Compendium of the project **{{ PLEASE ADD A FEW WORDS }}**

### How to cite

Please cite this compendium as:

> **{{ PLEASE ADD A CITATION }}**

### Content

This repository is structured as follow:

- [`data/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/master/data):
  contains all raw data required to perform analyses

- [`analyses/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/analyses/):
  contains R scripts to run each step of the workflow

- [`outputs/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/outputs):
  contains all the results created during the workflow

- [`figures/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/figures):
  contains all the figures created during the workflow

- [`R/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/R):
  contains R functions developed especially for this project

- [`man/`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/man):
  contains help files of R functions

- [`DESCRIPTION`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/DESCRIPTION):
  contains project metadata (author, date, dependencies, etc.)

- [`make.R`](https://github.com/emiel200/EpiverseTraceWorkshop/tree/main/make.R):
  main R script to run the entire project by calling each R script
  stored in the `analyses/` folder

### Usage

### Usage

First, clone this repository. You can follow [steps on creating a new
Rstudio Project from a GitHub
repository](https://www.epirhandbook.com/en/version-control-and-collaboration-with-git-and-github.html?q=clone#clone-from-a-github-repository).

Then, run:

``` r
source("make.R")
```

### Notes

- All required packages, listed in the `DESCRIPTION` file, will be
  installed (if necessary)
- All required packages and R functions will be loaded
- Some analyses listed in the `make.R` might take time
