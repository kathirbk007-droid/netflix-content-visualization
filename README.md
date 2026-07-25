[README_Netflix.md](https://github.com/user-attachments/files/30373524/README_Netflix.md)
# Netflix Content Visualization

Data Science internship project — **Thiranex**

## About the Project

An intermediate-level visualization project exploring a Netflix content catalog — analyzing content types, genres, countries, ratings, and trends over time to understand the platform's content strategy.

## What This Project Does

- Cleans raw catalog data (missing values, duplicates)
- Visualizes:
  - Movies vs TV Shows split (pie chart)
  - Titles added to Netflix by year (trend line)
  - Top genres (bar chart)
  - Top 10 content-producing countries (bar chart)
  - Content rating distribution (bar chart)
  - Movie duration distribution (histogram)
  - TV show seasons distribution (count plot)
  - Genre popularity over release years (heatmap)
- Summarizes key insights about the catalog's composition and trends

## Tools & Libraries Used

- **Python**
- **Pandas / NumPy** – data handling
- **Matplotlib / Seaborn** – visualization
- **Jupyter Notebook** (via Google Colab)

## Files in This Repo

| File | Description |
|---|---|
| `Netflix_Content_Visualization.ipynb` | Main notebook — full analysis with explanations and 8 charts |
| `raw_netflix_titles.csv` | Original raw dataset (before cleaning) |
| `cleaned_netflix_titles.csv` | Cleaned dataset |
| `netflix_insights_report.txt` | Plain-text summary of key findings |

## Key Findings

- Movies make up ~70% of the catalog, TV Shows the remaining ~30%.
- **Comedy** is the most common genre on the platform.
- **Canada** is the top content-producing country in this dataset.
- **2024** saw the highest number of titles added, reflecting continued catalog growth.
- The average movie runs about 119 minutes.

## How to Run

1. Open `Netflix_Content_Visualization.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload `raw_netflix_titles.csv` to the Colab session (Files panel → upload icon)
3. Run all cells (**Runtime → Run all**)

## Author

Submitted as part of a Data Science internship task at Thiranex.
