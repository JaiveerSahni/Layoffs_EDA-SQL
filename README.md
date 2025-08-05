# Portfolio Project: Exploratory Data Analysis (EDA) of Global Layoffs
This project performs exploratory data analysis (EDA) on a dataset of global layoffs. Using SQL, we explore trends, major events, and interesting patterns, such as identifying the companies with the largest layoffs, industry and country-level impacts, as well as identifying potential outliers.

## Project Overview
- The goal of this project is to:
- Practice SQL-based data exploration and analysis techniques
- Uncover insights related to layoffs over a recent period
- Visualize and summarize data trends, patterns, and outliers

 ## Key EDA questions addressed include:
- Which companies had the largest single and cumulative layoffs?
- Which countries, locations, or industries were most affected?
- Did any companies completely shut down (100% laid off)?
- How do layoffs trend over time (monthly/yearly)?
- Are there notable stories or outliers in the data?

## Dataset
The dataset (layoffs_staging2) contains records of layoffs from companies around the globe. The key columns include:

- company – Company name

- date – Date of the layoff event

- total_laid_off – Number of employees laid off

- percentage_laid_off – What portion of the company was laid off

- funds_raised_millions – Capital raised (in millions)

- location, country – Location/country of company

- industry – Business sector

- stage – Startup stage/phase

## File Structure
Portfolio-Project-EDA.sql: All SQL queries and analysis steps

## How to Use
### 1.Requirements
- A SQL database (tested on MySQL and compatible systems)
- The world_layoffs.layoffs_staging2 table loaded with the dataset

### 2.Running the analysis
- Open and execute the queries in Portfolio-Project-EDA.sql step by step in your SQL editor or IDE.
- Review the results of each query to follow the exploration or copy/paste manually into your SQL console.
- Each section includes comments explaining the purpose of the queries and what to look for.

## Key Analysis Sections
- Simple Aggregates: Maximum layoffs, minimum/maximum percentage layoffs, companies with total shutdown
- Groupings by Company, Location, Country, Industry, and Stage: Who was affected most and where
- Annual and Monthly Trends: Layoff patterns over time
- Advanced Queries: Top companies per year, rolling layoff totals, and rankings for deeper insight

## Example Insights
- Companies with the largest layoff events both in a single event and cumulatively
- Trends showing which years/months saw peak layoff activity
- Which countries and industries have been impacted the most

## Notes
- The script includes both simple and advanced queries (using GROUP BY and window functions/CTEs).
- Feel free to customize queries for visualization tools or as needed for your business questions.


