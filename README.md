# Video Game Success Analysis
Data Science - Exam Project

## Overview

This project explores the key factors that influence the commercial success of video games. By combining multiple datasets, the analysis investigates how attributes such as genre, platform, release year, and review scores relate to global sales.

The project applies data science techniques including data cleaning, exploratory data analysis (EDA), statistical testing, and an attempt at predictive modeling.

**Note**: There is a possibility this project does not include predictive modelling.

## Techniques Used
- Data cleaning
- Exploratory Data Analysis (EDA)
- Statistical analysis (p-values, correlations)
- Modeling

## How to run

### 1. Install dependencies
```
pip install -r requirements.txt
```
### 2. Open in jupyter lab or notebook
```
jupyter lab
```
or
```
jupyter notebook
```

## Technologies

- Python 3.14+
- Jupyter Notebook/Lab
- Pandas
- Numpy
- Matplotlib
- SciPy
- scikit-learn

## Repository Structure

```
data/  # Datasets
    raw/
    temp/
    clean/
video_games_analysis.ipynb - Main project
requirements.txt - Required libraries
```

## Methodology

1. Data Cleaning
- Handling missing values
- Converting data types
- Removing inconsistencies

2. Data Integration
- Merging datasets on shared attributes (e.g., name, platform, year)
- More cleaning

3. EDA
- Distribution of sales
- Trends over time
- Genre and platform comparisons
- Correlation analysis

4. Statistical Analysis
- Hypothesis testing
- Correlation metrics
- P-value interpretation

5. Modeling
- Built a linear regression model to estimate global sales from review-related features (critic_score, user_score, critic_count, user_count)

## References

### Dataset 1: Video Game Sales (VGChartz)
- Original source: VGChartz game database (web scraping)
- Scraped dataset: https://zenodo.org/records/5898311
- Kaggle mirror: https://www.kaggle.com/datasets/thedevastator/global-video-game-sales
- Scraping tool: https://github.com/GregorUT/vgchartzScrape

This dataset contains global and regional video game sales data, including platform, genre, publisher, and release year. It serves as the primary source for analyzing commercial performance.

### Dataset 2: Video Game Sales and Ratings
- Author: Samir Kumar Shukla
- Kaggle: https://www.kaggle.com/datasets/thedevastator/video-game-sales-and-ratings
- Additional source: https://data.world/sumitrock

This dataset extends the analysis with critic and user review scores, enabling the exploration of relationships between game quality metrics and sales performance.

## Additional References

- Pandas: https://pandas.pydata.org/docs/
- Matplotlib: https://matplotlib.org/stable/index.html
- NumPy: https://numpy.org/doc/
- SciPy: https://docs.scipy.org/doc/scipy/
- Course materials: https://softuni.bg/trainings/5022/data-science-march-2026