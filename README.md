# 2021 BRFSS Data Analysis Projects

**Academic coursework | Private repository**

This repository contains two data analysis projects using the **2021 Behavioral Risk Factor Surveillance System (BRFSS)** dataset. The analyses were developed in **R** and documented using **Quarto (`.qmd`)**.

> **Access:** This repository is intended to remain private in accordance with my school's guidance. Please do not redistribute coursework or supporting materials without appropriate permission.

## Data source and attribution

The data used in these projects comes from the **Centers for Disease Control and Prevention (CDC)**, specifically the **2021 Behavioral Risk Factor Surveillance System (BRFSS)**. BRFSS collects survey information about health-related behaviors, chronic health conditions, and preventive service use among U.S. adults.

**Official source:** [CDC — 2021 BRFSS Survey Data and Documentation](https://www.cdc.gov/brfss/annual_data/annual_2021.html)

The CDC page provides the 2021 survey data and supporting documentation, including the codebook and survey overview. The CSV in this repository is the dataset used for this coursework; its exact preparation and format should be checked against the original CDC files.

**Suggested data citation:** Centers for Disease Control and Prevention (CDC). *Behavioral Risk Factor Surveillance System (BRFSS), 2021 survey data and documentation*. https://www.cdc.gov/brfss/annual_data/annual_2021.html

## Projects

### Mental Health Analysis
**File:** [`Mental_Health_Analysis.qmd`](Mental_Health_Analysis.qmd)

Explores associations between the number of days respondents reported poor mental health during the past 30 days (`MENTHLTH`) and three predictors:

- Household income category (`INCOME3`)
- Age group (`_AGE_G`)
- Exercise participation (`EXERANY2`)

The analysis includes data preparation and cleaning, exploratory visualizations, summary statistics, examination of potential outliers, comparison of three regression models, model diagnostics, and predictions for three hypothetical individuals. Results describe **associations, not causal effects**. The selected linear regression model had limited explanatory power, and its predictions should be interpreted cautiously.

### General Health Analysis
**File:** [`General_Health_Analysis.qmd`](General_Health_Analysis.qmd)

A separate R/Quarto analysis of the 2021 BRFSS data focused on general health. Refer to the Quarto file for its specific research questions, selected variables, methods, and findings.

## Repository contents

| File | Description |
| --- | --- |
| `Mental_Health_Analysis.qmd` | Mental health analysis in Quarto |
| `General_Health_Analysis.qmd` | General health analysis in Quarto |
| `brfss2021.csv` | BRFSS 2021 data used for the coursework |
| `BRFSS_2021 Codebook.pdf` | Variable coding reference |
| `BRFSS_2021 Data Overview.pdf` | Dataset overview |
| `BRFSS_2021 Questionnaire.pdf` | Survey questionnaire |
| `README.md` | Project overview and instructions |
| `.gitattributes` | Git text and binary file handling rules |

## Tools and workflow

- **R** for statistical analysis
- **Quarto** for reproducible analysis documents
- **tidyverse / dplyr / ggplot2** for data manipulation and visualization
- **Base R statistical functions** for regression, diagnostics, and predictions

## Working with the projects

1. Install R, Quarto, and the R packages required by the `.qmd` documents.
2. Open either `.qmd` file in RStudio or another Quarto-compatible editor.
3. Keep `brfss2021.csv` in the expected file location, or update the dataset path in the code.
4. Run the code or render the Quarto document to reproduce the analysis.

**Note:** Package requirements and data paths should be checked in the individual Quarto files. Reproducibility may depend on the versions of R and the packages used.

## Data and interpretation

BRFSS is a survey dataset. Findings from these analyses should be interpreted in light of survey design, self-reported responses, variable coding, and model assumptions. Unweighted analyses should not automatically be treated as representative population estimates.

## Academic use

These projects were completed for academic learning and demonstrate skills in data cleaning, exploratory analysis, visualization, statistical modeling, and interpretation. Repository visibility must remain **Private** in GitHub settings; this README and `.gitattributes` do not enforce access restrictions.
