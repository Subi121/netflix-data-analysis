# 🎬 Netflix Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-9cf)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

An **Exploratory Data Analysis (EDA)** project on Netflix's content catalog using Python and Plotly. Analyzes content trends, genre popularity, country contributions, director insights, and rating patterns across **7,789 titles** from **2008 to 2021**.

---

## 🎯 Objective
 
- Analyze Netflix content distribution across Movies and TV Shows
- Identify top genres, directors, and content-producing countries
- Understand rating patterns and target audience segmentation
- Track content growth trends from 2008 to 2021

---

## 📁 Dataset

| Property | Value |
|---|---|
| Records | 7,789 |
| Columns | 11 |
| Coverage | 2008 – 2021 |
| Fields | Title, Type, Director, Cast, Country, Rating, Duration, Genre, Year |

---

## 🛠️ Tech Stack

* Python
* Pandas
* Plotly Express (interactive charts)
* Matplotlib / Seaborn
* Google Colab

---

## 📂 Project Structure
 
```
netflix-data-analysis/
├── Netflix Dataset.csv                       # Dataset file
├── Netflix_Dataset_Analysis.ipynb            # Main analysis notebook
├── Netflix_Project_Problem_Statement.docx    # Project problem statement
├── requirements.txt                          # Python dependencies
└── README.md
```
 
---

## 📊 Analysis & Visualizations

| Chart | Description |
|---|---|
| Movies vs TV Shows | Distribution and yearly breakdown of content type |
| Top Genres | Most frequent genres across the catalog |
| Top 10 Directors | Raúl Campos & Jan Suter lead with 18 titles |
| Country-wise Contributions | Top content-producing countries |
| Ratings Distribution | Breakdown of content ratings (TV-MA, TV-14, etc.) |
| Movie Duration | Histogram of movie lengths in minutes |
| Content Growth | Movies vs TV Shows released per year (2008–2021) |

---

## 🔍 Key Insights

* Netflix catalog is **movie-heavy** with significant TV Show growth post-2015
* **Raúl Campos & Jan Suter** are the most prolific directors with 18 titles
* **United States** is the top content-contributing country
* Content additions peaked around **2018–2019**
* Most content is rated **TV-MA** and **TV-14**, targeting adult audiences

---

## 🚀 Run the Project

```bash
git clone https://github.com/Subi121/netflix-data-analysis.git
cd netflix-data-analysis
pip install -r requirements.txt
jupyter notebook Netflix_Dataset_Analysis.ipynb
```
 
Or open directly in  **Google Colab**:
1. Open the notebook **Netflix_Dataset_Analysis.ipynb** in **Google Colab**
2. Upload `Netflix DataSet.csv`
3. Run all cells to generate interactive charts

---

## 🔭 Future Improvements

* Sentiment analysis on titles and descriptions
* Predict content type using ML classification
* Time-series forecasting of content growth
* Add genre-based recommendation system

---

## ⚠️ Disclaimer
* This is an independent data analysis project completed during an internship at **VOIS (Vodafone Intelligent Solutions)**.  
* Not affiliated with or endorsed by Netflix, Inc.  
* Dataset was provided as part of the internship program.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
