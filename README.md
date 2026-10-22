# 🎬 Movie Data Analysis with Python

## 📌 Project Overview

This project focuses on exploring, cleaning, and analyzing a movie dataset using Python and popular data analysis libraries. The goal is to understand the dataset, identify patterns, and answer important questions about movie genres, popularity, ratings, and release years.

This project is part of my journey to learn **Data Analysis and Data Science** through real-world datasets.

## 🎯 Project Objectives

- Explore the structure and characteristics of the dataset.
- Identify and handle missing values.
- Remove duplicate records where appropriate.
- Clean column names and correct data types.
- Analyze movie genres, popularity, and vote averages.
- Identify the year with the highest number of movie releases.
- Visualize important patterns and distributions.

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **JupyterLab** — Interactive development environment

## 📂 Project Structure

```text
movie-data-analysis/
│
├── movie_analysis.ipynb
├── mymoviedb_cleaned.csv
├── README.md
└── .gitignore
```

- `movie_analysis.ipynb` — Notebook containing the data exploration, cleaning, analysis, and visualizations.
- `mymoviedb_cleaned.csv` — Cleaned dataset exported from Pandas.
- `README.md` — Project documentation.
- `.gitignore` — Specifies files Git should ignore.

## 📊 Dataset Description

The project uses a movie dataset containing information about movies, including:

| Column | Description |
|---|---|
| `Title` | Movie title |
| `Release_Date` | Movie release date |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of votes |
| `Vote_Average` | Average vote score |
| `Original_Language` | Original language of the movie |
| `Genre` | Movie genre or genre combination |
| `Overview` | Brief movie description |
| `Poster_Url` | Movie poster URL |

The exact columns and data types depend on the original dataset.

## 🔍 Key Questions

This analysis aims to answer the following questions:

1. Which genre or genre combination appears most frequently?
2. Which movie has the highest vote average?
3. Which movie has the highest popularity score, and what is its genre?
4. Which movie has the lowest popularity score, and what is its genre?
5. In which year were the most movies released?

## 🧹 Data Cleaning Process

The data cleaning process may include:

- Creating a copy of the original dataset.
- Removing unnecessary spaces from column names.
- Checking missing values.
- Identifying and handling duplicate records.
- Converting `Release_Date` into a datetime format.
- Converting numerical columns into appropriate numeric data types.
- Removing or handling invalid values based on the analysis requirements.
- Exporting the cleaned dataset to a CSV file.

Cleaning decisions are made based on the data and the purpose of the analysis.

## 📈 Data Analysis and Visualization

Pandas is used to summarize and analyze the dataset, while Matplotlib and Seaborn are used to visualize distributions and patterns.

Possible visualizations include:

- Genre frequency distribution.
- Movie popularity comparison.
- Vote average analysis.
- Number of movies released per year.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/asifhas2/Solve_netflix_dataset_kaggle_day2.git
```

### 2. Navigate to the project directory

```bash
cd Solve_netflix_dataset_kaggle_day2
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyterlab
```

### 4. Start JupyterLab

```bash
jupyter lab
```

Open `Netflix.ipynb` and run the notebook cells in order.

## 💾 Export the Cleaned Dataset

The cleaned DataFrame can be saved as a CSV file using Pandas:

```python
df_clean.to_csv("mymoviedb_cleaned.csv", index=False)
```

## 🚀 Future Improvements

- Perform deeper statistical analysis.
- Investigate relationships between popularity, vote averages, and vote counts.
- Explore trends in movie releases over time.
- Improve visualizations and create an interactive dashboard.
- Develop additional insights from the cleaned dataset.

## 👨‍💻 Author

**Asif Hasan**

Software Engineering Student  
Daffodil International University

**Interests:** Python, Data Analysis, Data Science, and Machine Learning.

## 📄 License and Dataset Attribution

The dataset belongs to its original creator or provider. Please check the dataset's license and attribution requirements before redistributing it.

This project is intended for educational and learning purposes.

---

⭐ If you find this project useful, feel free to explore the notebook and share feedback.
