# Titanic Dataset - Exploratory Data Analysis

This repository contains an **exploratory data analysis (EDA)** project on the famous Titanic dataset. The goal is to analyze passenger data to uncover patterns, outliers, and relationships that can provide insights into survival rates.

![Titanic](NYT_titanic.png)

> The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after colliding with an iceberg during its maiden voyage from Southampton to New York City. Over 1,500 of the 2,224 passengers and crew died, making it one of the deadliest peacetime maritime disasters in history.  
> Source: [Wikipedia](https://en.wikipedia.org/wiki/RMS_Titanic)

## Project Goals

- Perform structured **exploratory data analysis** using Python and the **Seaborn** library.
- Compare **subgroups of passengers** based on features like age, class, and sex.
- Identify **patterns, trends, and outliers** in the dataset.
- Gain hands-on experience with **data visualization techniques**.

## Dataset Overview

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

All inferred data types match the nature of the data, ensuring consistency and accuracy.

## How to Use

1. Clone this repository:  
   ```bash
   git clone <repository-url>
