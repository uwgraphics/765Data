# Datasets curated for CS765 Data Visualization at UW-Madison

These datasets were originally created for CS765 in 2025. We are using the same ones in 2026.

A discussion of how these two data sets were used in 2025
available at: https://pages.graphics.cs.wisc.edu/765-25/pages/two-data-sets/

The idea is that there are two data sets: one in "wide" format, and the other in "tall" format.

## US Census Data

Files are in the [census-usda/](census-usda/) folder. See the readme file: [census-usda/readme.md](census-usda/readme.md)

The data was obtained from US census data: https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/ and processed by course staff. In 2026, we removed Group Quarters population estimates and added some poverty data. Some columns were also renamed.

Data file: [census-usda/full_census_dataset.csv](census-usda/full_census_dataset.csv) (state-level totals: [census-usda/aggregate_census_dataset.csv](census-usda/aggregate_census_dataset.csv))

## Global Lifespan Data

Use of this data set was inspired by a a [class assignment](https://teaching.vda.univie.ac.at/vis/25s/a1.html) at the University of Vienna.

We provide two versions:

- A version that has data post-1960 that includes a breakdown by sex. This data is derived from data from the World Bank.
- A version that has data for a range of years (including historical data from select countries) that was obtained from Our World in Data.

### World Bank Data

Files are in the [life-expectancy-worldbank/](life-expectancy-worldbank/) folder. See the readme file: [life-expectancy-worldbank/readme.md](life-expectancy-worldbank/readme.md)

The data was obtained from Global lifespan data: https://data.worldbank.org/indicator/SP.DYN.LE00.IN

Data file: [life-expectancy-worldbank/lifespan_dataset_1960.csv](life-expectancy-worldbank/lifespan_dataset_1960.csv)

### Our World in Data Data

Their web page (with some visualizations and explanations) is: https://ourworldindata.org/life-expectancy. We downloaded the data in September, 2025.

Files are in the [life-expectancy-owid/](life-expectancy-owid/) folder.

Their Readme: [readme.md](life-expectancy-owid/readme.md)

Their Data: [life-expectancy-owid.csv](life-expectancy-owid/life-expectancy-owid.csv)
