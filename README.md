# Datasets curated for CS765 Data Visualization at UW-Madison

A collection of datasets for class assignments in [CS765](https://pages.graphics.cs.wisc.edu/765-26/).

1. Life Expectancy Data - two versions
   1. World Bank - 1960-2023, split by sex (male, female, and both)
   2. Our World in Data - many years (back to the 1500s for a few countries), both sexes combined
2. Census Data (State and County Level statistics)
   1. Composite Data Set - large data set from many sources with many variables, 2000-2024
   2. USDA Data Set - older data set, fewer variables, fewer years

These data sets are being used in CS765 in 2026. We do not recommend students use the USDA data set.

Datasets 1.1, 1.2, and 2.2 were originally created for [CS765 in 2025](https://pages.graphics.cs.wisc.edu/765-25/pages/two-data-sets/).

The composite census data set (2.1) was built by Claude under the direction of course staff (see its readme).

CS765 course material · AI use: [pages.graphics.cs.wisc.edu/765-26/ai/de](https://pages.graphics.cs.wisc.edu/765-26/ai/de/)

## US Census Data

We provide data, aggregated at both the state and county level, for a wide range of variables including population and population change (births, deaths, and migration), education, employment and unemployment, poverty, income, and how rural or urban each county is. The composite version adds age, race and ethnicity, housing costs, and presidential election results.

We provide two versions:

- A composite data set, assembled in 2026 from several federal sources, with about 50 variables for every county, for every year from 2000 to 2024.
- The older data set used in 2025, derived from USDA files, which has fewer variables and only one or a few years for most of them.

### Composite County Data

Files are in the [census-composite/](census-composite/) folder. See the readme file: [census-composite/readme.md](census-composite/readme.md), which describes every column and which years have data.

The data comes in several shapes (tall and wide, all variables or a core set, every year or only election years) for both counties and states. If you are not sure where to start, try [census-composite/county_wide_compact_snapshot.csv](census-composite/county_wide_compact_snapshot.csv).

### USDA Data

This is an older data set - the composite data set is built from the same source material, and includes more variables with a more complete set of years.

Files are in the [census-usda/](census-usda/) folder. See the readme file: [census-usda/readme.md](census-usda/readme.md)

The data was obtained from US census data: <https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/> and processed by course staff. In 2026, we removed Group Quarters population estimates and added some poverty data. Some columns were also renamed.

Data file: [census-usda/full_census_dataset.csv](census-usda/full_census_dataset.csv) (state-level totals: [census-usda/aggregate_census_dataset.csv](census-usda/aggregate_census_dataset.csv))

## Global Lifespan Data

Use of this data set was inspired by a a [class assignment](https://teaching.vda.univie.ac.at/vis/25s/a1.html) at the University of Vienna.

We provide two versions:

- A version from the World Bank that covers 1960-2023 and is split by sex: each country has separate values for males, females, and both sexes combined.
- A version from Our World in Data that covers many more years, with historical data for some countries going back centuries, but only for both sexes combined.

### World Bank Data

Files are in the [life-expectancy-worldbank/](life-expectancy-worldbank/) folder. See the readme file: [life-expectancy-worldbank/readme.md](life-expectancy-worldbank/readme.md)

The data was obtained from Global lifespan data: <https://data.worldbank.org/indicator/SP.DYN.LE00.IN>

It covers 1960-2023 for 266 countries and regional groupings (such as "Sub-Saharan Africa" or "High income"). Each country and year has three values: male, female, and both sexes combined (the `Sex` column).

Data file: [life-expectancy-worldbank/lifespan_dataset_1960.csv](life-expectancy-worldbank/lifespan_dataset_1960.csv)

### Our World in Data Data

Their web page (with some visualizations and explanations) is: <https://ourworldindata.org/life-expectancy>. We downloaded the data in September, 2025.

It covers 265 countries and regions through 2023, with one value per country and year (both sexes combined; no breakdown by sex). Most countries start in 1950, but 95 have earlier historical estimates, some going back to the 1700s (Sweden from 1751) and the United Kingdom to 1543. Early data is sparse: many countries have only scattered years before 1950.

Files are in the [life-expectancy-owid/](life-expectancy-owid/) folder.

Their Readme: [readme.md](life-expectancy-owid/readme.md)

Their Data: [life-expectancy-owid.csv](life-expectancy-owid/life-expectancy-owid.csv)
