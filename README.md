# Countries Data Extraction

Data extraction and exploration of a countries dataset using NumPy and Pandas.

## Dataset
Source: Kaggle - [All Countries Details](https://www.kaggle.com/datasets/adityakishor1/all-countries-details)

The dataset has country-level details such as capital city, region, continent, currency, population, political leader, democracy score, land use and economic indicators.

## Tools Used
- Python
- NumPy
- Pandas
- Jupyter Notebook

## What I Did
- Loaded the dataset using `pd.read_csv()`
- Boolean filtering to find the capital cities of the most and least populated countries
- Sorted countries by `democracy_score` in descending order using `sort_values()`
- Counted the number of unique regions and the number of countries in a region using `value_counts()`
- Filtered all countries of a given region (Eastern Europe)
- Used `nlargest()` to find the second most populated country and its political leader
- Found countries with missing political leader values using `isna()`
- Searched text in a column using `str.contains()` (countries with "Republic" in their full name)
- Created a subset DataFrame of African countries and found the most populated one

## How to Run
1. Clone this repository
2. Download the dataset from the Kaggle link above and save it as `Countries.csv` in the same folder
3. Open `Countries_DataExtraction.ipynb` in Jupyter Notebook and run all cells
