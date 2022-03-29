# Inter- and intraindividual relationships between vagally-mediated heart rate variability and self-regulatory processes: An ecological momentary assessment
This respository includes the supplementary materials of the article:

Menghini, L., Fuochi, G., Sarlo, M. Inter- and intraindividual relationships between vagally-mediated heart rate variability and self-regulatory processes: An ecological momentary assessment

# CAUTION: WORK IN PROGRESS

## Supplementary materials
The repository includes the following materials:

1. `1ESMeasures`: Experience sampling measures used in the study (screenshots in Italian and English translations).

2. `2preProcessing`: R code and generated report with full outputs of the pre-processing procedures applied to the raw data (available upon request to the corresponding author). The **data pre-processing report** is [depicted at this page](https://Luca-Menghini.github.io/vmHRV-selfRegulation/2preProcessing/preProcessing.html).

3. `3data`: datasets (in both .RData and .csv format) generated with the data pre-processing script: 
    - `long`: long-form dataset with time-varying variables and repeatedly recorded time-invariant variables
    - `wide`: wide-form dataset with demographic variables and individual averages of time-varying variables

4. `4psychomeDesc`: R code and generated report  with full outputs of the psychometric and descriptive analyses applied to the pre-processed data, including the inspection of univariate and bivariate distributions. The **psychometrics and descriptives report** is [depicted at this page](https://Luca-Menghini/vmHRV-selfRegulation/) and can be reproduced by running the .Rmd script on the two datasets in `3data`.

5. `5regModels`: R code and generated report with full outputs of the generalized linear mixed-effects regression (GLMER) analysis of the pre-processed data. The **data analysis report** is [depicted at this page](https://Luca-Menghini/vmHRV-selfRegulation/) and can be reproduced by running the .Rmd script on the two datasets generated with the `4psychomeDesc` script.

## External resources
The scripts included in this repository are based on the following external resources:

### PIBID-APP
Shiny app used to pre-process the blood volume (BVP) pulse data and derive the HRV measures used in the analyses.

### R packages
The data pre-processing and data analysis scripts are based on the following R packages:
