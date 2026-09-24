# Netflix Content Analysis

## Overview

This project explores Netflix's catalog of movies and TV shows using exploratory data analysis. The dataset includes details such as content type, country, rating, genre, release year, and duration.

The analysis examines the composition of Netflix's catalog, common content categories, geographic distribution, and changes in the catalog over time. The goal is to identify meaningful patterns and summarize them using data-driven insights and visualizations.

## Dataset

The dataset contains 8,807 Netflix movies and TV shows. Each row represents one title and includes fields such as title, type, director, cast, country, date added, rating, duration, genres, and description.

## Objectives

- Compare the number of Movies and TV Shows.
- Identify common ratings, countries, and genres.
- Explore how many titles were added to Netflix over time.
- Compare release years by content type.
- Examine the distribution of movie durations.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

The notebook inspects data quality, cleans whitespace, converts `date_added` to a date, and answers eight basic exploration questions. It includes six charts: content types, ratings, countries, genres, titles added by year, and movie durations.

## Key Findings

- Movies make up 69.6% of the catalog (6,131 titles); TV Shows make up 30.4% (2,676 titles).
- `TV-MA` is the most common content rating, with 3,207 titles.
- The United States is listed for the most titles (3,689), followed by India (1,046).
- International Movies is the most common genre category, appearing 2,752 times.
- Netflix added the most titles in 2019, with 2,016 additions recorded in the dataset.
- Movie durations have a median of 98 minutes and an average of about 99.6 minutes.

## Project Structure

```text
Netflix_Data_Analysis/
|-- data/
|   `-- netflix_titles.csv
|-- notebooks/
|   `-- netflix_content_analysis.ipynb
|-- README.md
`-- requirements.txt
```

## How to Run

1. Create and activate a Python virtual environment.
2. Install the packages: `pip install -r requirements.txt`.
3. Start Jupyter from the project folder: `jupyter notebook`.
4. Open `notebooks/netflix_content_analysis.ipynb` and run all cells.
