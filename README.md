# Exploring Health Outcomes with R | BRFSS 2021

**R · tidyverse · ggplot2 · Quarto · Linear & Logistic Regression**

I used the CDC's **2021 Behavioral Risk Factor Surveillance System (BRFSS)** data to investigate how everyday behaviors and demographic factors relate to self-reported health. These two case studies show my process—from cleaning survey responses and visualizing patterns to evaluating statistical models and communicating their limitations.

## Projects

### [Mental Health Analysis](Mental_Health_Analysis_Portfolio.qmd)
**Question:** How are income, age, and exercise associated with the number of poor mental-health days reported in the past month?

- Cleaned and analyzed **339,216** survey responses; explored distributions, group differences, and outliers.
- Compared **three linear regression models** and generated predictions for hypothetical individuals.
- **Key takeaway:** The strongest model explained **6.83%** of the variation—useful for exploring associations, but not precise individual predictions.

### [Health Outcome Predictor](Health_Outcome_Predictor_Portfolio.qmd)
**Question:** How are fruit consumption and routine medical checkups related to self-rated general health?

- Cleaned and transformed survey variables, examined distributions, and evaluated modeling choices.
- Applied **linear and logistic regression** and used the logistic model to predict outcomes for five hypothetical profiles.
- **Key takeaway:** How a health outcome is defined changes the model and how its results should be interpreted.

## What I Demonstrated

**Data preparation:** Cleaning, recoding, missing-value handling  
**Exploration:** Summary statistics, visualization, outlier assessment  
**Modeling:** Regression, diagnostics, model comparison, prediction  
**Communication:** Reproducible Quarto reports and evidence-based interpretation

## Explore the Repository

| File | Contents |
| --- | --- |
| [`Mental_Health_Analysis_Portfolio.qmd`](Mental_Health_Analysis_Portfolio.qmd) | Mental-health case study and R code |
| [`Health_Outcome_Predictor_Portfolio.qmd`](Health_Outcome_Predictor_Portfolio.qmd) | General-health case study and R code |
| `brfss2021.csv` | Working dataset |
| `BRFSS_2021 Codebook.pdf`, `BRFSS_2021 Data Overview.pdf`, `BRFSS_2021 Questionnaire.pdf` | Survey documentation |

To reproduce the work, open a `.qmd` file in RStudio with the CSV in the same folder, install the required R packages, and render with Quarto.

## Data Source & Limitations

**Source:** Centers for Disease Control and Prevention (CDC), [2021 Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/annual_data/annual_2021.html).

These are **exploratory analyses of self-reported, observational data**. Associations do not demonstrate causation; the analyses are not survey-weighted national estimates. Model predictions should be interpreted cautiously.
