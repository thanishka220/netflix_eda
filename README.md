# Netflix Movies and TV Shows – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the *Netflix Movies and TV Shows* dataset.  
The objective is to understand data patterns, feature behavior, content trends, and identify important features that can be used for prediction tasks.

The analysis is carried out using Python libraries such as **Pandas** and **Matplotlib**.

---

## 📂 Dataset Information
- **Dataset Name:** Netflix Movies and TV Shows
- **Source:** Kaggle
- **Dataset Link:** https://www.kaggle.com/datasets/shivamb/netflix-shows
- **File Used:** netflix_titles.csv
- **Total Records:** 8,807
- **Total Features:** 12

### Key Columns
- `type` – Movie or TV Show  
- `title` – Name of the content  
- `release_year` – Year of release  
- `rating` – Age rating  
- `duration` – Duration in minutes or seasons  
- `listed_in` – Genre categories  
- `country` – Country of production  

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📊 EDA Tasks Performed

### 1. Data Loading and Inspection
- Loaded the dataset using Pandas
- Checked dataset shape, data types, and missing values

### 2. Distribution of Numerical Features
- Plotted histogram for `release_year`
- Analyzed how Netflix content is distributed across years

### 3. Categorical Feature Analysis
- Count plot for Movies vs TV Shows
- Count plot for content ratings

### 4. Outlier Detection
- Box plot created for movie duration
- Identified unusually long movie durations

### 5. Correlation Analysis
- Correlation heatmap plotted using numerical features
- Studied relationships between release year and duration

---

## 🔍 Key Insights
- Netflix content increased significantly after 2015
- Movies dominate the Netflix catalog compared to TV Shows
- Majority of content targets teenage and adult audiences
- Most movie durations fall between 80 and 120 minutes
- No strong correlation was observed between numerical features

---

## ⭐ Important Features for Prediction
- `type`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `country`

These features are useful for building classification or recommendation models.

---


