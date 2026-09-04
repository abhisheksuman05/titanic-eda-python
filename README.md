# Titanic Dataset: Mini Exploratory Data Analysis (EDA)

An exploratory data analysis project on the Titanic passenger dataset focusing on data cleaning, demographic grouping, and multi-variable visualization using Python.

---

## 📌 Project Overview
This project completes **Task 3 of the Data Science with Python Internship at MainCrafts Technology**. It builds upon baseline survival analyses to extract deeper demographic and sociological patterns regarding passenger survival rates aboard the Titanic[cite: 1].

---

## 🛠️ Key Requirements & Features
* **Data Cleaning & Handling Missing Values**[cite: 1]:
  * Imputed missing `Age` values using the column mean[cite: 1].
  * Dropped irrelevant and heavily sparse features (such as `Cabin`)[cite: 1].
* **Statistical Group Analysis (`groupby`)**[cite: 1]:
  * Survival rate segmented across age brackets (`Child`, `Teen`, `Young Adult`, `Middle Aged`, `Senior`)[cite: 1].
  * Survival rate across different embarkation ports (`Cherbourg`, `Queenstown`, `Southampton`)[cite: 1].
  * Survival impact of family size (`SibSp` + `Parch`)[cite: 1].
* **Visual Data Storytelling**[cite: 1]:
  * **Age Distribution**: Histogram with KDE showing passenger age spread[cite: 1].
  * **Correlation Heatmap**: Visualizing collinearity between numeric features[cite: 1].
  * **Family Survival Dynamics**: Bar plot showing survival probability as family size increases[cite: 1].

---

## 📊 Key Findings
* **Age Factor**: Children (ages 0–12) had the highest survival rate (~58%), reflecting the "women and children first" protocol. Seniors (60+) had the lowest survival rate (~23%).
* **Port of Embarkation**: Passengers boarding at Cherbourg (`C`) experienced the highest survival rate (~55%), largely influenced by a higher proportion of first-class ticket holders.
* **Family Size Impact**: Traveling alone yielded only a ~30% survival rate, whereas passengers in small families (1–3 relatives) had the highest survival rates (~55–72%). Large families (4+) saw survival chances drop below 20%.
