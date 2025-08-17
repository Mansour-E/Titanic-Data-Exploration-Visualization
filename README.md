# Titanic Dataset – Exploratory Data Analysis (EDA)

![Titanic](NYT_titanic.png)

> **RMS Titanic:** The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after colliding with an iceberg during its maiden voyage from Southampton to New York City. Over 1,500 of the 2,224 passengers and crew died, making it one of the deadliest peacetime maritime disasters in history.  
> Source: [Wikipedia](https://en.wikipedia.org/wiki/RMS_Titanic)

---

## 📑 Table of Contents

1. [Project Goals](#-project-goals)  
2. [Dataset Overview](#-dataset-overview)  
3. [Exploratory Data Analysis](#-exploratory-data-analysis)  
   - [Individual Variable Analysis](#individual-variable-analysis)  
   - [Survival Analysis](#survival-analysis)  
   - [Deck-wise Survival](#deck-wise-survival)  
   - [Class vs Age Analysis](#class-vs-age-analysis)  
4. [Insights and Discussion](#-insights-and-discussion)  
5. [How to Use](#-how-to-use)  
6. [Technologies](#-technologies)  

---

## 🎯 Project Goals

- Perform **structured exploratory data analysis** using Python and Seaborn.  
- Compare **passenger subgroups** based on features like age, sex, and class.  
- Identify **patterns, trends, and outliers** in the dataset.  
- Gain hands-on experience with **data visualization techniques**.

---

## 📊 Dataset Overview

The dataset includes the following columns:

| Column        | Data Type | Description |
|---------------|-----------|-------------|
| survived      | int64     | Survival (0 = No, 1 = Yes) |
| pclass        | int64     | Passenger class (1, 2, 3) |
| sibsp         | int64     | Number of siblings/spouses aboard |
| parch         | int64     | Number of parents/children aboard |
| age           | float64   | Passenger age |
| fare          | float64   | Ticket fare |
| sex           | object    | Gender |
| embarked      | object    | Port of embarkation |
| embarked_town | object    | Town of embarkation |
| alive         | object    | Survival status (Yes/No) |
| who           | object    | Person type (man, woman, child) |
| class         | category  | Ticket class |
| deck          | category  | Deck level |
| adult_male    | bool      | Is adult male? |
| alone         | bool      | Is traveling alone? |

---

## 🔎 Exploratory Data Analysis

### Individual Variable Analysis
Distribution of **age** and **fare** in the dataset:

![Age Distribution](charts/age_distribution.png)  
![Fare Distribution](charts/fare_distribution.png)

---

### Survival Analysis
Comparison of **survival rates** across different genders and classes:

![Survival by Gender](charts/survival_by_gender.png)  
![Survival by Class](charts/survival_by_class.png)

---

### Deck-wise Survival
Distribution of survivors across **different decks**:

![Deck Survival](charts/deck_survival.png)

---

### Class vs Age Analysis
Relationship between **class and age** of passengers:

![Class vs Age](charts/class_vs_age.png)

---

## 💡 Insights and Discussion

- **Women and children** had significantly higher survival rates than men.  
- **First-class passengers** had better survival chances compared to lower classes.  
- The **fare distribution** suggests wealthier passengers were more likely in higher classes.  
- Certain **decks** had disproportionately lower survival rates.  

---

## ⚙️ How to Use

Clone the repository and run the Jupyter Notebook:

```bash
git clone https://github.com/Mansour-E/titanic-eda.git
cd titanic-eda
jupyter notebook Titanic_EDA.ipynb
