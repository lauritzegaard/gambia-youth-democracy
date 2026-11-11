# Democratic Political Engagement in Post-Transition Gambia

Replication code for the paper "Democratic political engagement in post-transition Gambia" (Quantitative Methods II, Sciences Po; revised November 2026).

The analysis uses Afrobarometer Round 9 data for The Gambia (2022, N = 1,200) to examine whether young Gambians differ from older cohorts in their support for democracy and in unconventional political participation. It estimates survey-weighted logistic regressions (R, `survey` package) for:

- three levels of support for democracy (value-based, structural and process-related), and
- two forms of unconventional participation (attending a community meeting and joining others to raise an issue).

## Files

- `Quantitative_Skills_II_script_v2_2026.qmd`: Quarto script (data cleaning, models, figures, diagnostics)
- `Quantitative_Skills_II_script_v2_2026.pdf`: rendered output
- `gambia-youth-democracy.Rproj`: R project file

## Data

The data are not included in this repository, as Afrobarometer data are protected by copyright. To run the script, download the Gambia Round 9 dataset (`GAM_R9.data_2022.sav`) free of charge from https://www.afrobarometer.org/data/ and place it in a folder named `data/` inside the project.

Data source: Afrobarometer Data, The Gambia, Round 9, 2022, available at [http://www.afrobarometer.org.](https://www.afrobarometer.org/survey-resource/gambia-round-9-data-2023/)

## Requirements

R with the packages `tidyverse`, `haven`, `survey`, `stargazer`, `ggeffects`, `patchwork` and `car`. Open the `.Rproj` file and render the `.qmd` with Quarto.

## Author

Lauritz Elias Gaard
