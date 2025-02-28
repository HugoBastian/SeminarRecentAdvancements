# The Partisan Economy

This repository contains code and data for "The Partisan Economy: How Political Affiliation Shapes Perceptions of Financial Well-Being in the United States," a study examining how partisan bias influences Americans' assessments of their personal financial situations.

## Repository Structure

```
├── Code/
│   ├── DataTransformations.Rmd   # Creation of data subsets from GSS dataset
│   ├── Variables.Rmd             # Creation of partisan identifiers and other variables
│   ├── Regressions.Rmd           # Main regression models and predicted probabilities
│   └── RobustnessRegressions.Rmd # Additional models with time covariates and different year samples
│
└── DataSets/
    ├── subset_GSSdata.csv            # Initial subset from GSS cumulative dataset
    ├── subset_GSSdata_clean.csv      # Cleaned dataset with no missing observations
    ├── subset_final.csv              # Final dataset for main analysis (1973-2022)
    └── subset_final_postbush.csv     # Post-2001 subset for testing polarization hypothesis
```

## About the Project

This study uses General Social Survey (GSS) data from 1973 to 2022 to analyze how partisan identity shapes Americans' perceptions of their personal financial situation. The analysis applies ordered logistic regression models to test whether:

1. Individuals rate their financial situation more favorably when their preferred party holds the presidency
2. This partisan gap has widened over time (especially post-2001)
3. Stronger partisan attachment amplifies these effects

Results show significant partisan bias in financial perceptions, with effects intensifying in recent decades and among strong partisans.

## Data Source

The original data comes from the General Social Survey (GSS) cumulative dataset (1972-2022), which can be downloaded from the [GSS website](https://gss.norc.org/).

[SOURCE] Davern, Michael; Bautista, Rene; Freese, Jeremy; Herd, Pamela; and Morgan, Stephen L.; General Social Survey 1972-2022. [Machine-readable data file]. Principal Investigator, Michael Davern; Co-Principal Investigators, Rene Bautista, Jeremy Freese, Pamela Herd, and Stephen L. Morgan. NORC ed. Chicago, 2024. 1 datafile (Release 4) and 1 codebook (2022 Release 4).



