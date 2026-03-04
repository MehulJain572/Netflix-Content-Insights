# Netflix Content Insights: Exploratory Data Analysis (EDA)

## Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset. The goal is to uncover patterns in content distribution, growth trends over the last decade, and identify the leading genres and producing countries on the platform.

## Objective
To answer the following research questions:
1. What is the distribution between Movies and TV Shows?
2. How has the volume of content added to Netflix evolved over the years?
3. Which genres are the most popular in the Netflix library?
4. Which countries are the top contributors to Netflix content?

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib (Visualization)
- **Environment:** Jupyter Notebook / VS Code

## Key Insights
- **Content Growth:** There was a significant surge in content added to Netflix starting from 2015, peaking around 2019.
- **Global Leadership:** The United States and India are the primary producers of content on the platform.
- **Top Genres:** "International Movies" and "Dramas" are the most frequent categories, reflecting Netflix's focus on global expansion.
- **Distribution:** Movies make up approximately 70% of the total library compared to TV Shows.

## Data Cleaning Steps
- Removed duplicate entries.
- Handled missing values in the `date_added` and `country` columns.
- Standardized date formats and extracted `year_added` for time-series analysis.
- Utilized the `explode` function to accurately count multi-category genres.

## How to Run
1. Clone the repository.
2. Ensure you have `pandas` and `matplotlib` installed.
3. Place the `netflix_titles.csv` file in the project directory.
4. Run the `project.ipynb` notebook.