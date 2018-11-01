# Reproducible research in R for the social sciences

There are several reasons to make your research reproducible. First of all, you want to be able to reproduce how you evaluated your data years later. Many scientists store their documents in folders and subfolders without a certain order. If then errors occur in the data evaluation, you don't know when and where the error occurred. On the other hand, it should be possible for other people to understand your data analysis. As scientists, we want to know how you arrived at your results in order to make an informed decision about whether your data is trustworthy. 

This repository includes a template for R and R-Studio that gives you a pre-structuring for your own reproducible research. To learn more about reproducible research in R, visit [my course on Udemy](https://www.udemy.com/). 


## Overview

    project

    |- data              # raw and cleaned data
    |  - raw/            # raw data; should never be altered
    |  - clean/          # cleaned data, once created, don't alter it
    |
    |- data_analyses/    # all descriptive and inferential statistics
    |  - cleaning.R      # script to convert raw into cleaned data
    |  - eda.Rmd         # exploratory data analysis goes here
    |  - hypo_x.RMd      # executable RMarkdown for a specific hypothesis
    |
    |- man/              # manuscript for the study
    |  - figures/        # graphs, images designed for manuscript figures
    |  - tables/         # tables designed for manuscript figures
    | 
    |- meta/             # directories to store files for finances, probands acquisition, etc. 
    |
    |- reports/          # executable and formatted RMarkdown reports of your analyses
    |
    |- scratch/          # temporary files that can be safely deleted or lost
    |
    |- README.md         # top level description of your experiment
    

## Further information

* [http://ropensci.github.io/reproducibility-guide/sections/introduction/](http://ropensci.github.io/reproducibility-guide/sections/introduction/)
* [https://github.com/ropensci/rrrpkg](https://github.com/ropensci/rrrpkg)