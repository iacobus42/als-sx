# About this repo
This repo contains the `R` code (as Quarto files, both `qmd` and `html`) used
to conduct analyses in the [pre-print](). The major research questions we 
attempt to address are:

1. Do ALS-like symptoms appear in insurance claims before a person is diagnosed
with ALS?

2. Does the risk for ALS vary between urban and non-urban areas?

3. Does the effect of ALS-like symptoms on future odds of being diagnosed with
ALS vary between urban and non-urban areas? 

# How to use the code
This repo contains four main files:

1. `build_cohort.qmd` and the rendered `build_cohort.html` contain the `R` code
used to identify ALS cases and find matching non-ALS controls. Also removes any
ALS cases with <365 days of enrollment between their first enrollment date and
the first ALS date,

2. `extract_covariates.qmd` and the rendered `extract_covariates.html` contain
the `R` code used to extract covariates used in the analysis. Also builds the
data sets used in the analysis.

3. `main_analysis.qmd` and the rendered `main_analysis.html` include the main
analysis reported in the paper and also all the non-survival sensitivity 
analyses.

4. `age_at_als_dx.qmd` and the rendered `age_at_als_dx.html` include the
age-at-diagnosis survival analyses.

# Links and references
* The pre-print can be found on [medRxiv]()
* Hosted versions of the HMTL can be found [here](https://www.jacobsimmering.com)

