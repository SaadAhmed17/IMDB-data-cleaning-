# IMDb Data Cleaning and Analysis

This project focuses on cleaning, processing, and analyzing a messy IMDb dataset containing information about 100 movies. The dataset includes various columns such as original title, release year, genre, duration, country, content rating, director, income, votes, and IMDb score — many of which contain inconsistent formats, missing values, or corrupted data.

## 📌 Objectives

- Clean and preprocess a real-world messy dataset
- Handle missing values, typos, special characters, and inconsistent formats
- Standardize categorical data and fix encoding issues
- Perform basic exploratory analysis on cleaned data

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- dateutil

## 🧹 Key Cleaning Tasks

- Removed extra spaces, symbols, and special characters from column names and values
- Replaced corrupted characters and encoding issues (e.g., `Ã©`, `ë`, `Inf`, etc.)
- Parsed inconsistent date formats in the `Release_year` column
- Handled missing and invalid entries in numerical columns like `Duration` and `Income`
- Standardized genres and exploded them for frequency analysis
- Unified `Content_rating` categories (e.g., `Unrated`, `Approved`, `#N/A`)
- Cleaned `Votes` and `Score` for numerical analysis

## 📊 Analysis & Results

After cleaning, basic aggregations were performed to understand:

- Average movie durations
- Top countries and directors by movie count

## 📁 Dataset

Original dataset taken from [Kaggle](https://www.kaggle.com/datasets/davidfuenteherraiz/messy-imdb-dataset/data) under the name **Messy IMDB Dataset**.

## 🚀 How to Run

1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Open `imdb_cleaning.ipynb` or run scripts in VS Code / Jupyter Notebook

## ✅ Status

✔️ Data cleaning complete  
✔️ Ready for further analysis or visualization

## 📄 License

This project is for educational and portfolio use only.
