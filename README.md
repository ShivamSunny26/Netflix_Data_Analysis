# 🎬 Netflix Titles – Exploratory Data Analysis (Python)

This project explores the **Netflix Titles dataset** using Python and Jupyter Notebook 📊.
The aim was to practice **real-world data cleaning and exploratory analysis** and understand how Netflix content is distributed across **time, countries, genres, and audience ratings**.

The dataset contains messy and missing values, making it a good representation of real industry data.

---

## 🔍 What this project covers

✅ Cleaning and preprocessing real-world data
✅ Handling missing and inconsistent values
✅ Exploratory Data Analysis (EDA)
✅ Creating clean, readable visualizations
✅ Extracting basic business insights

---

## 🛠 Tools used

* 🐍 Python
* 📑 Pandas
* 📈 Matplotlib
* 🎨 Seaborn
* 📓 Jupyter Notebook

---

## 📂 Dataset

* Source: **Netflix Titles dataset (Kaggle)**
* ~8,800 records of Movies and TV Shows
* Includes:

  * Type (Movie / TV Show)
  * Country 🌍
  * Release year & date added
  * Rating 🔞
  * Duration ⏱
  * Genres 🎭

Several columns had missing or mixed-format values, which required cleaning before analysis.

---

## 🧹 Data cleaning approach

Key steps performed:

* Renamed columns for consistency
* Converted date fields into proper datetime format (stripping stray whitespace first)
* Filled missing values without dropping large amounts of data
* Moved 3 misplaced runtime values out of the `rating` column into `duration`
* Extracted numeric values from the `duration` column
* Treated Movies and TV Shows differently where required

🎯 Goal: **Prepare the data without losing useful information**

---

## 📊 Exploratory analysis

This analysis focuses on questions such as:

* 🎥 How is Netflix content split between Movies and TV Shows?
* 📈 How has content addition changed over time?
* 🌍 Which countries contribute the most content?
* ⏱ What is the typical duration of Netflix movies?
* 📺 How many seasons do most TV shows have?
* 👥 Which audience ratings dominate the platform?

All visualizations are designed to be **simple, clean, and dashboard-style**.

---

## 💡 Key observations

📌 Movies form a larger share of Netflix’s catalog
📌 Content additions increased sharply after 2015
📌 Peak growth occurred around **2018–2020**
📌 The **USA, India, and UK** are major content contributors
📌 Most movies are between **80–120 minutes**
📌 Many TV shows have **1–2 seasons**
📌 Netflix mainly targets **teen and adult audiences**

---

## 📁 Project structure

```
Netflix_Data_Analysis/
│
├── netflix.ipynb
├── netflix_titles.csv
├── requirements.txt
├── LICENSE
└── README.md
```

Run the notebook from the project root (it reads `netflix_titles.csv` from the current directory):

```
pip install -r requirements.txt
jupyter notebook netflix.ipynb
```

---

## 🎯 Why this project

This project helped me practice:

* Working with unclean, real-world datasets
* Performing structured EDA before modeling
* Turning raw data into understandable insights

It is part of my **data analytics learning journey** 🚀.

---

## 🔮 Next steps

* Genre analysis by country 🌍
* Text analysis on descriptions (NLP)
* Interactive dashboard (Power BI / Tableau)
* Applying similar analysis to other datasets

---

## 🤝 Contact

If you have feedback or suggestions, feel free to connect 🙂

🔗 **LinkedIn:** *[Shivam Kumar](https://www.linkedin.com/in/shivamkumar2607/)*

---



