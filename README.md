# CROB DATA – ASA International Data Quest Türkiye 2026

## Statistical Analysis of Global Population Dynamics

This project investigates global population dynamics using the United Nations World Population Prospects 2024 dataset.

The study focuses on population growth, international migration, demographic aging, and changes in life expectancy during the COVID-19 period.

## Research Objectives

- Investigate the relationship between migration and population growth.
- Examine the demographic factors associated with population growth.
- Analyze differences in demographic aging across countries and over time.
- Evaluate changes in life expectancy during and after the COVID-19 pandemic.

## Dataset

**Source:** United Nations – World Population Prospects 2024

- Countries and areas: 237
- Period: 1950–2100
- Overall dataset scope: 35,787 observations
- Filtered analytical dataset: 17,538 observations

The dataset includes demographic indicators such as population size, fertility, birth and death rates, life expectancy, median age, and migration.

**Important:** Values after 2023 are projections rather than observed historical data.

[United Nations World Population Prospects 2024](https://population.un.org/wpp/)

## Methodology

The study applies statistical analysis and machine learning techniques.

### 1. Descriptive Statistics and Correlation Analysis

- Examined global population distributions and demographic differences.
- Analyzed relationships between life expectancy, infant mortality, fertility, and median age.
- Identified influential demographic patterns and historical outliers.

### 2. Migration and Population Growth

- Used regression analysis to investigate the relationship between migration and population growth.
- The migration model achieved an R² of approximately 0.42.
- Examined lagged migration variables and their relationship with subsequent population growth.
- Distinguished statistical association from causal interpretation.

### 3. Population Growth Modeling

Compared the following models:

- Linear Regression
- Random Forest
- Gradient Boosting

Fertility and median age emerged as important structural demographic variables.

The addition of migration substantially increased R²; however, this result was interpreted in light of the accounting relationship between population growth, natural increase, and net migration.

### 4. Demographic Aging

Variance decomposition was used to examine differences in median age.

- Between-country component: approximately 68%
- Between-year component: approximately 19%

Within-country analyses also examined fertility, life expectancy at age 65, infant mortality, and net migration.

### 5. COVID-19 and Life Expectancy

- Life expectancy declined in 195 of the 237 countries and areas examined.
- Median life expectancy increased by approximately 1.66 years between 2021 and 2023.
- 24 countries remained below their 2019 life expectancy level in 2023.

## Key Findings

The findings highlight the importance of fertility, age structure, and life expectancy in explaining global demographic differences.

Migration is an important component of population change, but its statistical contribution must be interpreted carefully because of its mathematical relationship with population growth.

The COVID-19 pandemic was associated with a widespread decline in life expectancy, followed by recovery in most countries.

## Limitations and Data Ethics

- UN projections are distinguished from historical observations.
- Regional aggregates were excluded where necessary to prevent double counting.
- Small-population areas were evaluated separately.
- Statistical associations are not interpreted as proof of causality.
- High R² values are interpreted cautiously when mathematical identities may contribute to model performance.
- Migration is treated as human movement rather than as an inherently negative phenomenon.

## Tools and Methods

- Python
- Data Analysis and Visualization
- Descriptive Statistics
- Correlation Analysis
- Regression Analysis
- Random Forest
- Gradient Boosting
- Variance Decomposition

## Project Materials

- `presentation.pdf` – Project presentation
- `figures/` – Selected visualizations
- `data_sources.md` – Dataset sources and information

---

**Project:** CROB DATA – ASA International Data Quest Türkiye 2026  
**Dataset:** United Nations World Population Prospects 2024
