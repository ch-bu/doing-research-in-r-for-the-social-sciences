# Reproducible research in R for the social sciences

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
    
