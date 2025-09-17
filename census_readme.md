## Introduction

This dataset was created by merging four separate files from the [USDA Economic Research Service]("https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/"). The data was collected at the county level, though state-level data is also available. 

It is worth noting that counties vary greatly in population and size. In addition, there are various regions that are not strictly 'counties', because US state governments have a great deal of control over county creation. For example, during the period this dataset covers, Connecticut went from having 8 counties to having 9 planning regions, with no 1-1 correlations. The dataset also includes Washington, D.C. and Puerto Rico, which are not states or part of states but are controlled by the US federal government.

## How was this modified?

The TA (Cat) joined the four datasets on FIPS Code and removed some redundant columns. Some columns were also renamed in an attempt to unify the naming scheme.The area names were manually edited to remove any non-English characters, but the rest of the data is untouched. We assume that the state-level aggregations are correct; they were included in the initial dataset and are also unmodified.

## Columns

As a wide dataset, there are quite a few columns, a subset of which is explained below. Previously, we had a link to detailed documentation from the USDA, but it has been moved and possibly deleted.

* FIPS Code - Stands for "Federal Information Processing System". This is a 5 digit string (any leading zeros are part of it), and each county has a unique FIPS code. This is the ID column, as counties do not necessarily have unique names.
* 2023 Rural-urban Continuum Code - A 9-category variable that, according to the USDA website, "distinguish[es] U.S. metropolitan (metro) counties by the population size of their metro area, and nonmetropolitan (nonmetro) counties by their degree of urbanization and adjacency to a metro area."
* 2023 Urban Influence Code - A 12-category variable (that was condensed into 9 categories in 2024) that classifies counties based on their resident count and their distance from (or status as) a metropolitan area.
* Bachelor's degree or higher, 1990 - The count of residents who achieved that education level in the year listed
* Domestic migration 2019 - The number of people who moved to the county from elsewhere in the US. The "year" indicated here is from July 1, 2018 to June 30, 2019.
* Natural Change Rate 2023 - The difference between birth and death rates, that is, the population change rate not counting migration
* Unemployed 2023 - The count of people in the county that are searching for work and have no current employment. Unemployment rate is also available in the dataset.
