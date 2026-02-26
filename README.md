# 🎌 Anime Insights: Data Wrangling & Duration Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Project Overview
This project focuses on the end-to-end data wrangling process of a raw Anime dataset. The primary challenge involved extracting structured information (episode counts and airing timelines) from highly unformatted, concatenated string columns.

> **Key Achievement:** Successfully transformed raw "Title" strings into a structured dataset featuring precise episode counts and calculated airing durations in months.

---

## 🛠️ Tools & Technologies
* **Language:** Python
* **Libraries:** * **Pandas & NumPy:** Core data manipulation and cleaning.
    * **DateTime & Dateutil:** Complex temporal calculations and date parsing.
* **Environment:** Jupyter Notebook.

---

## 🚀 Key Features
* **Complex String Parsing:** Engineered custom extraction functions to isolate data points hidden within nested parentheses and concatenated strings.
* **Temporal Engineering:** Converted "Airing Period" strings (e.g., "Apr 2009 - Jul 2010") into a numerical `Months` column using `relativedelta`.
* **Data Type Optimization:** Cleaned and cast extracted features into appropriate numerical formats (`int32`) for analysis.
* **Aggregated Insights:** Identified top-tier performers based on scores and total content volume.

---

## 🏗️ Project Structure
```text
├── data/
│   └── anime.csv             # Raw dataset with concatenated title strings
├── notebooks/
│   └── main.ipynb            # Primary wrangling & extraction logic
├── README.md                 # Project documentation
└── requirements.txt          # Environment dependencies

⭐ If you found this project helpful, consider giving it a star!