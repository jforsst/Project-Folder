# Carbon Emissions of Top Emitting Countries

Jessica Forsstrom and Marianna Ahlquist 2022-12-06

<!-- Short Description  -->

This project is looking at the trends and total amounts of carbon
emissions from countries around the world. Source data can be found in
the bp Statistical World Energy Review of 2021. hello this is a test

*Updated on 2022-12-06 00:24:34*

<!-- README.md is generated from README.Rmd. Please edit that file -->

## Table of contents

-   [General info](#general-info)
    -   [Methods](#methods)
    -   [Analysis](#analysis)
    -   [Project Description](#project-description)
        -   [Instructions for use](#instructions-for-use)
        -   [Directory](#directory)
            -   [Contact](#contact)

## General info 

This project aims to show the magnitude of carbon emissions
comparatively between countries both over time and overall.

## Methods 

-   Cleaning and trimming in Excel, coverting to .csv file
-   tidyverse in R Studio used to create tidy data, pivot_longer to
    mutate the data
-   ggplot to plot the graphs and bar charts

## Analysis 

-   Finding which countries emit the most each carbon emissions each
    year, then looking at total emissions from 1965 to 2021 and finding
    the top 5 countries that emit the most carbon emissions. Lastly,
    looking at the trends of these top five countries over the time
    period.

## Project Description 

-   Exploring the trend of carbon emissions over time in the top carbon
    emitting countries
-   Modeling includes bar graphs with frequency, bar graph with emission
    values, and a line graph over time with ggplot
-   Challenges include accounting for the USSR and Russian Federation
    because their data is not complete for the studied time period
-   Potential next stpes include comparing this data to carbon emissions
    per capita, looking at the relationship carbon emissions have with
    economic growth, or developing strategies to mitigate carbon
    emissions particularly in large emitting countries

## Instructions for use 

-   Download csv files from the data folder, then download the
    Rmarkdown!

## Directory 

``` bash
Project-Folder/ 
├─ .Rhistory 
├─ analysis/ 
│ ├─ EDA-BP-Analysis.Rmd 
├─ data/ 
│ ├─ co2_2.csv 
│ ├─ energydata2.csv 
├─ renv/ 
├─ .gitignore 
├─ .Rprofile 
├─ README.md 
├─ README.Rmd 
├─ README.html 
├─ R.RProj 
├─ renv.lock 
├─ reproducibility.Rmd
```

## Contact 

Created by [Marianna Ahlquist, Jessica Forsstrom](website_URL)
