# Healthcare Analytics: Doctor Visits Analysis

An Exploratory Data Analysis (EDA) project designed to investigate patient healthcare utilization trends, demographics, and insurance coverage factors influencing doctor consultation frequencies.

## 📌 Project Overview
This repository contains a comprehensive data analysis pipeline that evaluates 5,190 patient records. By examining metrics such as reported illnesses, reduced-activity days, income, age, gender, and insurance statuses, this project uncovers key drivers behind medical visits to assist in healthcare planning and resource allocation.

## 📊 Dataset Description
The dataset contains 5,190 observations with 12 primary features:

| Feature | Type | Description |
| :--- | :--- | :--- |
| `visits` | Integer | Number of doctor visits during the target period |
| `gender` | Categorical | Gender of the patient (`female` / `male`) |
| `age` | Float | Standardized age scale |
| `income` | Float | Annual income (scaled) |
| `illness` | Integer | Number of illnesses reported in the past 2 weeks |
| `reduced` | Integer | Days of reduced activity due to illness |
| `health` | Integer | General health status score |
| `private` | Categorical | Private health insurance cover (`yes` / `no`) |
| `freepoor` | Categorical | Free government cover due to low income (`yes` / `no`) |
| `freerepat` | Categorical | Free government cover due to age/pension (`yes` / `no`) |
| `nchronic` | Categorical | Non-chronic conditions present (`yes` / `no`) |
| `lchronic` | Categorical | Limiting chronic conditions present (`yes` / `no`) |

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Processing:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`

## 📈 Key Analysis Steps
1. **Data Cleaning & Verification:** Inspected missing values, data types, and index column removals.
2. **Univariate Analysis:** Analyzed visit distribution frequencies and overall demographic splits.
3. **Bivariate & Multivariate Analysis:** Explored relationships between illness severity, reduced activity days, insurance coverage, and consultation counts.
4. **Correlation Assessment:** Mapped continuous and mapped binary categorical variables to isolate key consultation predictors.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/mrsonu-boop/Healthcare-Analytics-for-Doctor-Visits.git](https://github.com/mrsonu-boop/Healthcare-Analytics-for-Doctor-Visits.git)
   cd Healthcare-Analytics-for-Doctor-Visits
