## Name 

``` Samuel Getnet Id/0127/12 ``` 

## HIV Data Analysis

This repository contains Python code for analyzing HIV-related data, specifically focusing on cases, deaths, people living with HIV, and antiretroviral therapy (ART) coverage. The data is organized by WHO region and year.

## Quastions 
1. How does the distribution of people receiving ART vary across different WHO regions?
2. Which WHO region has consistently shown the highest number of HIV cases over the years?
3. What trends can be observed in the number of children receiving ART and the coverage among children across different regions?
4. Are there specific regions where pediatric HIV cases and ART coverage differ significantly?
5. Which countries consistently rank among the top 10 for the highest HIV cases?
6. What factors could contribute to the variations in the number of people receiving ART among different regions?
7. How does the estimated number of children needing ART and the actual number of children receiving ART compare in various regions?
8. Are there regions where the percentage of people receiving antiretrovirals is lower than expected?
9. How do trends in HIV cases, deaths, and living with HIV differ between high-income regions (e.g., Europe and Americas) and lower-income regions (e.g., Africa and South-East Asia)?


## Data Sources

The analysis utilizes the following datasets:
- ```no_of_cases_adults_15_to_49_by_country_clean.csv```
- ```no_of_deaths_by_country_clean.csv```
- ```no_of_people_living_with_hiv_by_country_clean.csv```
- ```art_coverage_by_country_clean.csv```
- ```art_pediatric_coverage_by_country_clean.csv```
- ```prevention_of_mother_to_child_transmission_by_country_clean.csv```

## Libraries Used

- `numpy` for numerical operations
- `pandas` for data manipulation
- `seaborn` and `matplotlib` for data visualization

## Analysis Overview

The code performs the following analyses:

1. Heatmaps showcasing trends of HIV cases, deaths, and people living with HIV by WHO region and year.
2. Bar plots illustrating the number of people receiving ART and the estimated ART coverage among people living with HIV by region.
3. Analysis of pediatric data, including children receiving ART and ART coverage among children by region.
4. Evaluation of prevention measures, including the number of people receiving antiretrovirals and the percentage received by region.

## Top Trends

The code identifies and visualizes top trends, including:

- Top 10 countries with the highest HIV cases.
- Countries with the highest and lowest HIV deaths.
- Countries with the highest population living with HIV.
- Countries with the highest and lowest ART coverage.

## Region-Specific Analysis

The code further explores and visualizes trends in each WHO region, including Europe, Americas, Eastern Mediterranean, South-East Asia, Western Pacific, and Africa.

## Conclusion

This analysis provides insights into the trends of HIV-related data, enabling a better understanding of the prevalence, impact, and response to HIV across different regions and over time. The following questions guide the exploration of the data:

