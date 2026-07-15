# Global-Layoffs-Portfolio-Project---Data-Exploration.sql

Layoffs Exploratory Data Analysis
This project explores global layoffs from 2020–2023 using SQL. The goal was to understand trends, identify patterns, and analyze which companies, industries, and countries were most impacted — especially during the COVID‑19 period.

The analysis includes:

    Dataset exploration

    Identifying extreme cases (100% layoffs)

    Aggregating layoffs by company, industry, country, and funding stage

    Time‑based analysis (yearly, monthly, cumulative trends)

    Ranking companies by total layoffs per year

    Building and refining window‑function logic to identify top 5 companies each year

Key Questions Explored
1. What companies, industries, and countries experienced the most layoffs?
    Summed total layoffs by company

    Summed layoffs by industry

    Summed layoffs by country

    Identified companies with 100% workforce layoffs

2. What is the date range of the dataset?
     Earliest and latest dates fall between 2020–2023, aligning with major COVID‑related workforce reductions.

3. How did layoffs progress over time?
     Monthly totals

     Cumulative rolling totals

     Year‑over‑year comparisons

4. Which companies had the highest layoffs each year?
     Built multiple versions of ranking logic


SQL Techniques Used
    Aggregations (SUM, MAX, MIN)

    Filtering and ordering

    Date extraction (YEAR, SUBSTRING)

    Common Table Expressions (CTEs)

    Window functions (DENSE_RANK, cumulative SUM OVER)

    Progressive query refinement to show analytical thought process

  Summary of Insights:
    Layoffs peaked during 2020–2021, aligning with early COVID impact.

    Certain industries (tech, consumer services) showed significantly higher totals.

    Several companies experienced full workforce layoffs (100%).

    Rolling totals highlight sharp increases during specific months.
