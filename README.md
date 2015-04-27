# iwseco2015
Replication package for IWSECO2015 paper "On the Development and Distribution of R Packages: An Empirical Analysis of the R Ecosystem"

## `data` directory

**bioconductor-number-packages.csv** - Number of packages for each category of packages for each version of BioConductor.
**bioconductor_annotation_description.csv** - Meta-data for the packages belonging to category "Annotated datasets" of BioConductor (2015-04-22). Extracted from the main website.
**bioconductor_description.csv** - Meta-data for the packages belonging to category "Software" of BioConductor (2015-03-18). Extracted from the main website.
**bioconductorsvn_description.csv** - (More) meta-data for the packages belonging to category "Software" of BioConductor (2015-03-18). Extracted from the SVN.
**cran-description.csv** - Meta-data for packages from CRAN, for all available versions until 2015-04-07. 
**cran-number-packages.csv** - Number of packages through time for CRAN.
**cran-snapshot-20150319.csv** - List of *CRAN-checked* packages (2015-03-19).
**github-RPackage-repository.csv** - List of GitHub repositories that contains an R package, with some meta-data (extracted using a list of R repositories built from GitHubArchive, see paper for details). Meta-data were retrieved the 2015-02-17.
**r-forge_description.csv** - Meta-data for packages from R-Forge, extracted from the SVN (2015-03-18).
**R-Packages.csv** - Meta-data for all packages from GitHub, R-Forge, BioConductor and CRAN (aggregated from the others .csv).
**R-Repositories.csv** - List of GitHub repositories that contains an R package. Same as github-RPackage-repository.csv without meta-data.

## `notebooks` directory

This directory contains some Python code needed to extract or manipulate the data. 

**Data - BioConductor SVN.ipynb** - Extract R package meta-data from BioConductor SVN.
**Data - BioConductor.ipynb** - Extract R package meta-data from BioConductor website.
**Data - GitHubArchive.ipyng** - Explain how to extract data from GitHubArchive.
**Data - R-Forge.ipynb** - Extract R package meta-data from R-Forge.
**Data - Rforge.ipyng** - Extract R package meta-data from RForge.
**IWSECO - Github Repositories and R Packages.ipynb** - Generate github-RPackage-repository.csv
**IWSECO - Packages evolution.ipynb** - Evolution of the number of repositories containing an R package on GitHub.
**IWSECO - Packages repartition.ipynb** - Repartition of the packages accross the considered sources of R packages.
**IWSECO - R Package Dependencies.ipynb** - Study of the dependency graph of R packages.
**IWSECO - Repository activity.ipynb** - Activity (creation, modification, ...) of repositories that contain an R package on GitHub.
