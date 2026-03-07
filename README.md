# Bellabeat Fitbit Data Analysis

This project analyzes fitness tracker data to identify activity, sleep, and health behavior patterns. The goal is to explore user habits and extract insights that could help companies like Bellabeat improve their products and marketing strategies.

The dataset used in this project comes from Fitbit fitness tracker data and contains information about daily activity, sleep, weight logs, and heart rate.

## Dataset

Dataset source:
[https://www.kaggle.com/datasets/arashnic/fitbit](https://www.kaggle.com/datasets/arashnic/fitbit)

The raw CSV files are not included in this repository.
To reproduce the analysis, download the dataset from Kaggle and place the files inside:

```
data/raw/
```

## Project Structure

```
bellabeat-analysis/
│
├── notebooks/
│   └── bellabeat_analysis.ipynb
│
├── data/
│   └── raw/              # ignored in git, place dataset here
│
├── .gitignore
└── README.md
```

## Tools Used

* Python
* Pandas
* Jupyter Notebook
* Data cleaning and exploratory data analysis (EDA)

## Analysis Overview

The notebook includes:

* Data loading
* Data cleaning and preprocessing
* Date formatting and normalization
* Exploratory analysis of:

  * Daily activity
  * Sleep patterns
  * Weight logs
  * Heart rate data
* Identification of usage trends and behavioral patterns

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/bellabeat-analysis.git
```

2. Download the dataset from Kaggle

[https://www.kaggle.com/datasets/arashnic/fitbit](https://www.kaggle.com/datasets/arashnic/fitbit)

3. Place the CSV files inside

```
data/raw/
```

4. Open the notebook

```
notebooks/bellabeat_analysis.ipynb
```

5. Run the cells to reproduce the analysis.

## Purpose

This project is part of a personal data analysis portfolio and demonstrates skills in:

* Data cleaning
* Exploratory data analysis
* Working with real-world datasets
* Using Python for analytical workflows
