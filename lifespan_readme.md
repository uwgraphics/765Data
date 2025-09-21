## Introduction

This is a tall dataset, containing multiple decades of life expectancy estimations for countries and regions around the world. The instructors have provided two different versions - unlike the census data, these are from different sources.



## Country Names and Standardization 
The World Bank dataset is different from the one used in the Tableau tutorial. The organizations that compiled and published the gathered lifespan estimations may not have had access to the exact same data, and they may have made decisions about presenting the data based on organizational or geopolitical biases. The data was initially created by a variety of groups including national offices and Eurostat, which may have had biases of their own.

Similar to the census dataset, many of the attributes can change due to politics (the names and borders of some of the countries involved, in particular, have gone through one or more changes). We are giving the data to you as we found it (aside from some formatting modifications). 

# World Bank Data (lifespan_dataset_1960)
This dataset was made available by the [World Bank]("https://data.worldbank.org/indicator/SP.DYN.LE00.IN"). It covers the years 1960-2023.

## How was this modified?

The TA merged three of the available datasets (Male, female, and total life expectancy), and changed the format from wide (with a column for each year) to tall. The "Sex" categorical variable was renamed for brevity (see below).

## Columns

* Country Name - An English term for the country or region (some of these are aggregated!)
* Country Code - A standardized three-letter abbreviation for the country or region
* Sex - One of "Male", "Female", or "Both"
* Year - The year to which the numerical data applies
* Life Expectancy (years) - The estimated average lifespan for residents in any given year. Many, many different variables are considered when calculating this number.

# Vienna Dataset (life-expectancy-1950.csv)

TODO
