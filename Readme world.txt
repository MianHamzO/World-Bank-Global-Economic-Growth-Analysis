Project Title
World Bank Global Economic Growth Dashboard
Project Overview

This project is an interactive Power BI dashboard developed using World Bank GDP datasets to analyze global economic growth trends across countries and regions over time.
The dashboard provides a comprehensive overview of economic performance using data visualization, DAX calculations, and interactive filtering techniques.

Objectives
Analyze global GDP trends over multiple years
Compare economic growth between regions
Explore country-level GDP performance
Create interactive and professional dashboards
Apply data modeling and DAX calculations in Power BI
Dashboard Pages

1. Global Overview
Provides high-level insights including:

Total GDP
GDP Growth %
Total Countries
Global GDP trend over time
GDP distribution by region
Interactive world map visualization
2. Regional Analysis

Focused on regional economic comparison:
GDP by region
Regional growth trends
Region ranking analysis
Treemap and ribbon charts
3. Country Insights

Detailed country-level analysis:
Top performing countries
GDP comparison between countries
Growth analysis
Decomposition tree for drill-down insights
Technologies Used
Microsoft Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Data Modeling
World Bank Open Data

DAX Measures Used
Total GDP:
Total GDP = SUM(GDP[GDP])
GDP Growth %:
GDP Growth % =
DIVIDE(
    [Total GDP] - [Previous Year GDP],
    [Previous Year GDP]
)

Total Countries:
Total Countries =
DISTINCTCOUNT(GDP[Country Code])

Skills Demonstrated:
Data Cleaning & Transformation
Data Modeling
Interactive Dashboard Design
Business Intelligence Reporting
DAX Calculations
Analytical Storytelling
Visual Analytics
Data Source

World Bank Open Data:

GDP datasets
Country metadata
Regional classifications
Outcome

The dashboard enables users to explore economic growth patterns globally and identify regional and country-level trends through interactive and visually engaging reports.