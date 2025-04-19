# Black-Friday-Sales-Analysis-Data-Analytics-with-Python

Welcome to the Black Friday Sales Analysis project — a data analytics deep-dive using Python and its powerful ecosystem of libraries. This project showcases essential data analysis skills, from data cleaning and transformation, to exploratory data analysis (EDA), and deriving actionable insights from real-world consumer behavior data.

Leveraging Python libraries like Pandas and NumPy this project walks through the analytical process step-by-step. The dataset, provided by a major retail store, contains purchase records for Black Friday — giving us a window into customer demographics, spending patterns, and preferences.

Whether you're a beginner exploring your first dataset or a professional refining your analytics pipeline, this project demonstrates practical data analysis workflows in Python that mirror real industry tasks.

## 📊 Dataset

- **Source**: [Black Friday Dataset](https://www.kaggle.com/datasets/sdolezel/black-friday)
- **Rows**: 550,069
- **Columns**: 12
- **Features**:
  - `User_ID`, `Product_ID`
  - Demographic: `Gender`, `Age`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`, `Marital_Status`
  - Product Categories: `Product_Category_1`, `Product_Category_2`, `Product_Category_3`
  - `Purchase` (target)

  ## 📊 Key Skills Demonstrated

- 🧹 Data Cleaning & Preprocessing
- 🔍 Exploratory Data Analysis (EDA)
- 🧠 Insight Extraction & Interpretation
- 🐍 Python Proficiency with:
  - Pandas
  - NumPy

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null values and cleaned the data.
- Plotted distributions for:
  - Gender-based purchases
  - Age vs. Purchase trends
  - Occupation vs. Purchase
  - City category-wise spending

## 📈 Key Insights

- Males tend to spend more on average than females.
- People aged 26–35 were the highest spenders.
- City category 'B' users spent more than 'A' or 'C'.
- Product category 1 had the most transactions.

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google colab Notebook

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/black-friday-analysis.git
cd black-friday-analysis
pip install -r requirements.txt
jupyter notebook notebooks/BlackFriday_Analysis.ipynb
