# Olympic Medal Analysis (1976–2008)

## Project Overview

This project presents a comprehensive analysis of the Summer Olympic Medals from 1976 to 2008. The goal is to uncover patterns, trends, and insights related to country performances, gender participation, and sports popularity across different Olympic years.

## Features

- Cleaned and preprocessed Olympic medal dataset (1976–2008)
- Country-wise total medal count analysis
- Medal distribution analysis (Gold, Silver, Bronze)
- Gender-wise participation and growth over time
- Year-wise medal trends and political impact (e.g., boycotts)
- Sport-wise popularity based on medal counts
- Visualizations including bar plots, line charts, and heatmaps

## Dataset

- Source: Kaggle or public Olympic data repositories
- File: Summer-Olympic-medals-1976-to-2008.csv
- Columns:
  - City
  - Year
  - Sport
  - Discipline
  - Event
  - Athlete
  - Gender
  - Country_Code
  - Country
  - Event_gender
  - Medal

## Data Cleaning

- Removed duplicates and null values
- Fixed encoding issues (ISO-8859-1)
- Standardized country names and codes
- Converted relevant columns to categorical types
- Added new columns:
  - Medal_Value (Gold=3, Silver=2, Bronze=1)
  - First_Name, Last_Name (from Athlete)
  - Decade (e.g., 1980s, 1990s)

## Exploratory Data Analysis (EDA)

Key Analyses:
- Top Countries by Total Medals
- Medal Distribution by Country
- Year-wise Medal Trends
- Gender-wise Participation Growth
- Top 5 Countries in Each Olympic Year
- Most Popular Sports Based on Medal Count

## Visualizations

- Bar plots for country and sport rankings
- Line charts for year-wise and gender-wise trends
- Stacked bar plots for medal distributions
- Heatmap for top 5 countries per year

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook or Python Script


