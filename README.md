# 📊 Black Friday Sales Data EDA

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Black Friday Sales Dataset** to uncover patterns in customer purchase behavior.  
The dataset contains transactional data of a retail store, including customer demographics, product categories, and purchase amounts.

**Objectives:**
- Understand customer demographics and purchasing trends.
- Identify high-value customer segments.
- Analyze product category performance.
- Derive insights for better marketing strategies.

---

## 📂 Dataset Information
**Shape:** `537,577 rows × 12 columns`  
**Source:** [Kaggle – Black Friday Dataset](https://www.kaggle.com/datasets/sdolezel/black-friday)

| Column Name                  | Description |
|------------------------------|-------------|
| `User_ID`                    | Unique customer ID |
| `Product_ID`                 | Unique product ID |
| `Gender`                     | Customer gender (`M`/`F`) |
| `Age`                        | Age group of the customer |
| `Occupation`                 | Occupation code of the customer |
| `City_Category`              | Category of the city (`A`, `B`, `C`) |
| `Stay_In_Current_City_Years` | Number of years customer stayed in current city |
| `Marital_Status`             | Marital status (`0` = Unmarried, `1` = Married) |
| `Product_Category_1`         | Main product category |
| `Product_Category_2`         | Secondary product category |
| `Product_Category_3`         | Tertiary product category |
| `Purchase`                   | Purchase amount |

---

## 🔍 Steps Performed

### 1. Data Loading & Inspection
- Loaded the dataset using **Pandas**.
- Checked shape, data types, and missing values.
- Identified numerical and categorical features.

### 2. Data Cleaning
- Filled missing values in `Product_Category_2` and `Product_Category_3` with appropriate methods.
- Converted data types where necessary.
- Removed irrelevant duplicates.

### 3. Exploratory Data Analysis
- **Univariate Analysis** – Distribution of individual columns.
- **Bivariate Analysis** – Relationship between customer demographics and purchases.
- **Multivariate Analysis** – Interaction of multiple factors influencing purchases.

### 4. Visualization
- Used **Matplotlib** and **Seaborn** for plots:
  - Count plots
  - Bar plots
  - Histograms
  - Heatmaps

---

## 📈 Key Insights
- **Male customers** accounted for higher overall sales compared to female customers.
- **Age group 26–35 years** had the highest purchase frequency and spending.
- **City Category B** customers had higher average purchases compared to other city categories.
- **Product Category 1** was the most purchased product category.
- Marital status had minimal effect on purchase amounts, but unmarried customers spent slightly more on average.

---

## 🛠️ Tools & Libraries Used
- **Python** (v3.x)
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced visualization
- **Jupyter Notebook** – Analysis environment

---


