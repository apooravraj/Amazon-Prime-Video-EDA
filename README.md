# Amazon Prime Video Catalog EDA

An exploratory data analysis of movies and TV shows in an Amazon Prime Video catalog dataset. The project uses Python, Pandas, and Matplotlib to study catalog characteristics, ratings, genres, countries, runtimes, and cast and director credits.

## Project files

- `amazon_prime_analysis.ipynb` — analysis notebook with data preparation, summary tables, and visualizations.
- `titles.csv` — title-level metadata.
- `credits.csv` — actor and director credits.

## Run the notebook

1. Install Python and the packages `pandas`, `matplotlib`, and `jupyter`.
2. Open the notebook in Jupyter Notebook or VS Code.
3. Keep both CSV files in the same folder as the notebook.
4. Run the notebook cells from top to bottom.

## Key findings

- The catalog contains more movies than shows.
- Movie runtimes are typically longer than individual show episode runtimes.
- Drama and comedy are among the most frequent genre tags.
- The United States is the most frequent production-country tag.
- IMDb and TMDB scores have a positive relationship, though the scores can differ.

## Limitations

This analysis describes catalog metadata and external IMDb/TMDB ratings. It does not include Prime Video viewing or engagement data, so these results should not be treated as measures of viewer demand or platform performance. Titles may have multiple genre and country tags, and some metadata is missing.

## Dataset source

Add the original dataset source and license here.
