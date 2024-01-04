## Global COVID Analysis With MS Excel.

This study examines the Covid-19 trend from January 2020 to August 2022, comparing confirmed cases to fatalities and recovered cases. This project provides a comprehensive overview of data analysis with MS Excel, covering techniques such as Pivot Tables, Power Query, and Dashboard creation.

## Data Sourcing 

The data set used for this Analysis was sourced from GitHub

Tools used for data cleaning and preparation: Microsoft Excel , Power Query.
The data was imported into Power Query as unprocessed data from the website, then renamed Confirmed, Death, and Recoveries, then combined into CombinedData. The data combination was then imported into Microsoft Excel.

The data was analyzed in MS Excel for misspellings, duplicates, and null values, and new columns were added for visualization, resulting in 330,327 rows for Confirmed and Death while 313,182 for Recoveries and 11 columns.

# Analysis

On the newly created worksheet, analysis was performed by summarizing the table using pivot tables to generate the following insights:

Top 10 Confirmed cases by country
Bottom 10 Confirmed cases by country
Distribution of Confirmed cases across the four years.
Confirmed cases, Death Cases, Recovered Cases by year.
Death cases by month in each year.

Later a dashboard as shown below.

![Screenshot 2024-01-03 190139](https://github.com/bonsoul/Global-Pandemic-Analysis/assets/83598526/d944285c-f0ca-44a4-ac3e-43adeecbfd41)
![Screenshot 2024-01-03 190045](https://github.com/bonsoul/Global-Pandemic-Analysis/assets/83598526/ab881a2e-d299-40e5-a784-99ea5445127c)

 ## Assamptions:

1. The data source was not accurate because confirmed cases was equal to death cases!
2. Incosistent Data - From the dashboard you can see bottom 5 countries had zero cases confirmed wich is not genuine!
