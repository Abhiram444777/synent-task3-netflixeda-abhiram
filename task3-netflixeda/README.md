# Synent Task 3: Netflix Exploratory Data Analysis

## Problem Statement
Explore the Netflix titles dataset to identify content patterns across title type, country, release year, rating, and genre, then summarize the main insights with analysis-ready visualizations.

## Dataset Details
- Dataset: Netflix Movies and TV Shows
- Source: [Kaggle Netflix Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Original size: 8,807 rows and 12 columns
- Input file: `netflix_titles.csv`

## Approach
1. Loaded the Netflix dataset and inspected column types.
2. Reviewed missing values and summary information.
3. Compared movies and TV shows in the catalog.
4. Identified the top content-producing countries.
5. Analyzed how Netflix content additions changed over time.
6. Studied title distribution by rating.
7. Extracted and compared the most common genres.
8. Created charts to support each finding.

## Results
- Movies form the larger share of the Netflix catalog.
- The United States contributes the highest number of titles.
- Content additions increased heavily in recent years, with a high point around 2019-2020.
- TV-MA and TV-14 are among the most common ratings.
- International Movies and Dramas appear frequently in the genre field.

## Files Included
- `netflix_titles.csv`: Raw dataset
- `netflix_eda.ipynb`: EDA notebook

## How to Run
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook netflix_eda.ipynb
```

Keep `netflix_titles.csv` in the same folder before running the notebook.
