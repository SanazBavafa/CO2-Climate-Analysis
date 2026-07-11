# CO2 Emissions and Global Temperature: A Data Analysis Project

## Overview
This project explores the relationship between global CO2 emissions and rising global temperatures using real-world climate datasets. Through data cleaning, exploratory analysis, and linear regression modeling with NumPy and Pandas, the project investigates how strongly CO2 emissions correlate with global warming trends from 1880 to 2023.

## Objectives
- Analyze long-term trends in global CO2 emissions and surface temperature anomalies
- Compare total and per-capita CO2 emissions across the top emitting countries (China, USA, and others)
- Calculate annual CO2 growth rates and identify historical turning points (e.g., WWI recovery, WWII impact)
- Fit a linear regression model to statistically test the relationship between CO2 emissions and global temperature

## Data Sources
- **CO2 emissions data:** Our World in Data
Source: https://ourworldindata.org/co2-and-greenhouse-gas-emissions
- **Global temperature data:** NASA GISTEMP (GLB.Ts+dSST)
Source: https://data.giss.nasa.gov/gistemp/  

## Methodology
1. Data loading and cleaning with Pandas
2. Merging and aligning CO2 and temperature datasets by year
3. Exploratory data analysis (trends, growth rates, country comparisons)
4. Linear regression modeling to quantify the CO2–temperature relationship
5. Visualization of results with Matplotlib

## Key Findings
- There is a clear positive linear relationship between CO2 emissions and global temperature from 1880 to 2023
- The average annual CO2 growth rate is about 2.9%, showing steady increases almost every year since 1880
- The fastest growth occurred in 1920 (16.6%), linked to industrial recovery after World War I
- The slowest/negative growth occurred in 1945 (-16.9%), linked to the impact of World War II
- China currently has the highest total CO2 emissions, while the United States has the highest per-capita emissions
- Emissions and temperatures rose slowly before 1950 and much more rapidly afterward, suggesting population growth alone does not explain warming — energy consumption and industrialization play a major role

## Project Structure
CO2-Climate-Analysis/
├── README.md
├── Notebooks
│   └── CO2 Emissions and Global Temperature.ipynb
├── slides/
│   └── CO2-GitHub-ppt.PDF
└── data/
    └── (دیتاست‌ها، اگر می‌خواهید آپلود کنید)

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Presentation
A summary of the analysis and findings is available in the accompanying slide deck: [`slides/CO2-GitHub-ppt.pdf`](slides/CO2-GitHub-ppt.pdf)

## Author
Sanaz Bavafa
