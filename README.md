# Virginia Health Insurance: Socioeconomic Drivers of Coverage

**[View the Website Here](https://alexastein12.github.io/health-insurance-coverage-virginia/)**

## Overview
This project investigates county-level healthcare disparities across Virginia's 133 counties and independent cities, focusing on the structural divide between public and private insurance coverage. Utilizing 5-Year Estimates (2020-2024) from the American Community Survey (ACS), the analysis identifies how socioeconomic factors—specifically education, poverty, and median income—drive regional insurance profiles.

## Methodology & Data
* **Data Sourcing:** Extracted and cleaned demographic and economic data from the ACS 2020-2024 dataset.
* **Geospatial Mapping:** Engineered a Tableau choropleth map to display the geographic clustering of public coverage rates across Southwest and Northern Virginia.
* **Statistical Animation:** Developed animated scatterplots using `gganimate` to track the relationship between educational attainment (bachelor's degrees) and insurance type, and generated a `ggcorrplot` correlation matrix to quantify socioeconomic relationships.
* **Interactive Web Apps:** Built embedded Shiny applications utilizing `plotly` to allow users to dynamically filter coverage gaps by population density and compare specific counties against state averages.

## Key Findings
* **The Uninsured Myth:** Uninsured rates are remarkably consistent across the state (averaging 6.9%), largely due to the 2019 Medicaid Expansion and ACA subsidies. The true geographic disparity lies in the ratio of public to private coverage.
* **Education & Income as Primary Drivers:** Public insurance heavily correlates with lower educational attainment (r = -0.75) and lower median household income (r = -0.82), while private insurance shows the exact opposite trend.
* **Density Disparities:** Rural counties exhibit significantly higher public insurance rates—with medians 10 to 12 points higher—compared to suburban and urban centers.

## Tools & Libraries
* **Languages & Software:** R, Tableau Public
* **Libraries:** `tidyverse`, `ggplot2`, `gganimate`, `ggcorrplot`, `shiny`, `plotly`
* **Deliverable:** R Markdown (github_document) and an interactive HTML document (with embedded Shiny apps and Tableau visualizations).
