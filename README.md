# CVD

This repository provides the processed dataset used in the study on county-level prediction of cardiovascular disease-related healthcare costs based on social determinants of health.

## Repository Contents

- `carecost.csv`: processed county-level dataset used for analysis and model development.

## Dataset Description

The dataset contains county-level predictors derived from publicly available sources and one outcome variable:

- **Rows:** 3141
- **Columns:** 21

### Outcome Variable

- `carecost`: total healthcare cost per capita

### Predictor Variables

#### Clinical and behavioral risk factors
- `cholesterol`: prevalence of high cholesterol
- `diabetes`: prevalence of diabetes
- `smoking`: prevalence of current smoking
- `obesity`: prevalence of obesity
- `inactive`: prevalence of physical inactivity

#### Socioeconomic indicators
- `lesshighschool`: percentage of adults with less than a high school education
- `gini`: Gini index
- `poverty`: poverty rate

#### Demographic composition
- `asian`: percentage of non-Hispanic Asian population
- `black`: percentage of non-Hispanic Black population
- `age65`: percentage of population aged 65 years or older
- `hisp`: percentage of Hispanic population
- `male`: percentage of male population
- `marri`: percentage of married adults

#### Social and structural indicators
- `racialseg`: racial and ethnic segregation index
- `socialvul`: social vulnerability index

#### Rural--urban category indicators
- `large central metro`
- `large fringe metro`
- `medium/small metro`
- `nonmetro`

## Data Sources

The processed dataset was constructed from publicly available data sources cited in the manuscript, including:

- CDC Interactive Atlas of Heart Disease and Stroke
- Centers for Medicare and Medicaid Services (CMS)
- American Community Survey (ACS)
- PolicyMap
- CDC Social Vulnerability Index (SVI)

## Notes

This repository contains the processed dataset only. Users should consult the original data providers for source data access, update history, and any applicable use conditions.

## Citation

If you use this dataset, please cite the associated manuscript.
