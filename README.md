# Cyclistic Bike-Share Analysis Case Study

This project is a case study for analyzing the bike-share data of a fictional company called Cyclistic, based in Chicago, IL, USA. The main objective is to understand how casual riders and annual members use Cyclistic bikes differently and derive insights to maximize the number of annual memberships.

## File Overview

### divvy_tripdata_analisys.Rmd

This R Markdown file contains the analysis of the Cyclistic bike-share data. The analysis is structured as follows:

1. **Introduction**
   - Overview of the case study and the fictional company Cyclistic.

2. **Scenario**
   - The main objective of the analysis: understanding the differences in bike usage between casual riders and annual members.

3. **Importing Libraries**
   - Libraries used: `tidyverse`, `skimr`, `rmarkdown`, `janitor`, `maps`, `highcharter`, `xts`, `scales`, `formattable`.

4. **Reading the Necessary Files**
   - Combining 12 individual CSV files (from May 2022 to April 2023) into a single dataframe for analysis.

5. **Data Cleaning and Preparation**
   - Filtering out rows with missing values.
   - Converting date columns to appropriate date-time formats.
   - Adding new columns for further analysis: ride length, weekday, start hour, month, year, date, and season.

6. **Analyzing the Data**
   - Visualizing null values and potential issues.
   - Filtering out unrealistic ride lengths (less than 60 seconds).
   - Analyzing the total rides per month, season, day of the week, and hour of the day.

7. **Time Series Analysis**
   - Plotting a time series to understand trends in bike usage over the last 12 months.

8. **Conclusion**
   - Insights derived from the analysis, including the best times and seasons for social media advertisements.

## Usage

To run the analysis, open the `divvy_tripdata_analisys.Rmd` file in RStudio or any other R Markdown compatible environment and knit the document to generate the HTML output.

## Requirements

- R
- RStudio (or any other R Markdown compatible environment)
- The following R packages: `tidyverse`, `skimr`, `rmarkdown`, `janitor`, `maps`, `highcharter`, `xts`, `scales`, `formattable`.

## Author

Gerson Ramos

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
