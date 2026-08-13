# Netflix Data Analysis — Auspify Technologies Internship

## 📌 Project Overview

This project was completed as part of my **Data Analysis Internship at Auspify Technologies**.

The project focuses on analyzing a Netflix titles dataset using Python and Pandas. The work includes data cleaning, content type analysis, country-wise analysis, and release-year trend analysis.

The project is currently completed for **Tasks 1–4**, satisfying the internship requirement of completing any 4 out of the 6 available tasks.

---

## 🎯 Objectives

The main objectives of this project are:

- Clean and prepare the Netflix dataset for analysis.
- Analyze the distribution of Movies and TV Shows.
- Identify countries with the highest amount of Netflix content.
- Analyze Netflix content trends by release year.
- Create meaningful visualizations.
- Extract useful insights from the data.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook
- GitHub

---

## 📂 Project Structure

```text
Auspify_Data_Analysis_Internship/
│
├── Task_1_Netflix_Cleaning/
│   ├── Dataset.csv
│   ├── cleaned_netflix.csv
│   ├── Task_1_Netflix_Data_Cleaning.ipynb
│   └── Screenshots/
│
├── Task_2_Content_Type_Analysis/
│   ├── cleaned_netflix.csv
│   ├── Task_2_Content_Type_Analysis.ipynb
│   └── Screenshots/
│
├── Task_3_Country_Analysis/
│   ├── cleaned_netflix.csv
│   ├── Task_3_Country_Analysis.ipynb
│   └── Screenshots/
│
└── Task_4_Release_Year_Analysis/
    ├── cleaned_netflix.csv
    ├── Task_4_Release_Year_Analysis.ipynb
    └── Screenshots/

```

## 📊 Tasks Completed
Task 1 — Netflix Data Cleaning & Preparation

The dataset was cleaned and prepared for further analysis.

Key Steps
Loaded the Netflix dataset using Pandas.
Inspected the dataset structure.
Checked for missing values.
Checked for duplicate records.
Standardized relevant categorical fields.
Cleaned and prepared the dataset.
Exported the cleaned dataset.
Final Dataset
Metric	Result
Rows	8,790
Columns	10
Duplicate Rows	0
Missing Values	0

Output file: cleaned_netflix.csv

Task 2 — Content Type Analysis

This task analyzes the distribution of Movies and TV Shows.

Results
Content Type	Number of Titles	Percentage
Movie	6,126	69.69%
TV Show	2,664	30.31%
Total	8,790	100%
Key Finding

Movies represent the majority of the content in the dataset, accounting for 69.69%, while TV Shows account for 30.31%.

Visualizations
Movies vs TV Shows bar chart
Movies vs TV Shows pie chart
Task 3 — Country-Wise Netflix Content Analysis

This task analyzes the distribution of Netflix content across countries.

Top 10 Countries
Rank	Country	Number of Titles
1	United States	3,240
2	India	1,057
3	United Kingdom	638
4	Pakistan	421
5	Not Given	287
6	Canada	271
7	Japan	259
8	South Korea	214
9	France	213
10	Spain	182
Key Finding

The United States has the highest number of Netflix titles in the dataset, followed by India and the United Kingdom.

The dataset also contains records where country information is listed as "Not Given".

Task 4 — Trend Analysis by Release Year

This task analyzes the number of Netflix titles by release year.

Key Results
Metric	Result
Earliest Release Year	1925
Latest Release Year	2021
Peak Release Year	2018
Titles in Peak Year	1,146
Top Release Years
Rank	Release Year	Number of Titles
1	2018	1,146
2	2017	1,030
3	2019	1,030
4	2020	953
5	2016	901
Key Finding

The dataset shows a strong increase in the number of titles toward the late 2010s, reaching a peak in 2018 with 1,146 titles. The number of titles then decreases in the subsequent years represented in the dataset.

📈 Visualizations

The project includes visualizations for:

Content type distribution
Movie vs TV Show proportions
Top countries by number of titles
Netflix content production by release year
Recent release-year trends

Screenshots of the analysis are included within the respective task folders.

📌 Key Insights
Movies dominate the dataset, representing 69.69% of the titles.
The United States has the largest number of titles among the countries represented.
India ranks second in the country-wise analysis.
Netflix content production increased considerably toward the late 2010s.
2018 was the peak release year in this dataset, with 1,146 titles.
The number of titles decreases after the 2018 peak in the years represented.

👨‍💻 Author

Aseem S.

Data Analysis Internship Project
Auspify Technologies
