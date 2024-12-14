# World Layoffs Analysis Project

## Overview
This project performs an end-to-end analysis of global layoffs trends using SQL. It includes data cleaning, trend analysis, and the generation of key insights from a dataset of global layoffs. The analysis highlights industries and regions most affected by layoffs and identifies patterns over time. This project aims to provide data-driven insights to inform business and policy decisions related to layoffs and workforce management.

## Key Insights
- **Maximum Laid-Off in One Day**: Identified the highest number of layoffs that occurred in a single day across all companies.
  
- **Total Laid-Off by Company**: Analyzed total layoffs per company, providing insights into the companies that were most affected by layoffs over the years.

- **Total Laid-Off by Industry**: Summarized layoffs across various industries, showing which sectors experienced the highest total layoffs.

- **Total Laid-Off by Country**: Highlighted the countries with the highest total layoffs, revealing global disparities in the layoffs' impact.

- **Total Laid-Off by Year**: Aggregated layoffs on a yearly basis to identify trends and peak years of layoff activity.

- **Total Laid-Off by Month**: Analyzed layoffs on a monthly basis to uncover patterns and fluctuations throughout the year.

- **Total Rolling Layoffs**: Performed a rolling analysis to track ongoing layoffs trends over a specified time period.

- **Top 5 Companies with Maximum Layoffs (Ranked per Year)**: Identified the top 5 companies with the highest layoffs each year.

- **Top 5 Industries with Maximum Layoffs (Ranked per Year)**: Analyzed the top 5 industries that saw the highest layoffs year by year.

## Files
- **world_layoffs_analysis.sql**: Contains SQL queries used to clean the data and generate insights. The script includes:
  - **Data Cleaning**: Resolves null values, trims extra spaces, and standardizes data.
  - **Trend Analysis**: Queries that provide the total layoffs by company, industry, country, and more.
  - **Insights Generation**: Queries to identify key trends, top companies, and industries with the most layoffs.

- **report.pdf** (Optional): A PDF report summarizing the analysis and key insights from the project.

## How to Use
1. **Download the Dataset**: Import your layoffs dataset into MySQL or another compatible database.
2. **Run the SQL Script**: Execute the queries in `world_layoffs_analysis.sql` to clean the data and generate the insights.
3. **Review the Insights**: Analyze the tables and results to understand the global layoffs patterns and trends.
4. **Optional**: Use the provided `report.pdf` for a summarized version of the findings.

## Prerequisites
- MySQL (or another compatible SQL database).
- The dataset should contain columns such as `company`, `industry`, `country`, `layoff_date`, `total_laid_off`, etc.

## License
This project is open source. Feel free to use, modify, and distribute it under the MIT License.
