# Data-cleaning-and-preprocessing-real-world-data
🚀 Indian Startup Funding Analysis using Python, Pandas & EDA

📌 Project Overview

This project focuses on performing Data Cleaning, Data Preprocessing, and Exploratory Data Analysis (EDA) on a real-world Indian Startup Funding dataset. The dataset contains intentionally messy data, making it an excellent case study for applying practical data analysis techniques using Python.

The objective was to clean the dataset, transform inconsistent values into a usable format, analyze startup funding trends, and generate meaningful business insights using Pandas and NumPy.

---

🎯 Objectives

- Clean and preprocess messy real-world data.
- Handle missing values and duplicate records.
- Standardize inconsistent categorical values.
- Convert currency and date columns into usable formats.
- Perform Exploratory Data Analysis (EDA).
- Answer industry-based business questions using Python.
- Improve practical knowledge of Pandas operations and data manipulation.

---

📂 Dataset

Dataset: Indian Startup Funding Dataset

The dataset contains startup funding information such as:

- Startup Name
- City
- Industry
- Funding Stage
- Funding Amount
- Funding Date
- Investors
- Founded Year

The dataset intentionally contains:

- Missing values
- Duplicate records
- Inconsistent city names
- Different industry spellings
- Currency symbols
- Multiple date formats
- Mixed categorical values

---

🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

📊 Project Workflow

1. Data Loading

- Imported dataset
- Inspected rows and columns
- Checked missing values
- Identified duplicate records

---

2. Data Cleaning

Performed extensive preprocessing including:

- Renamed columns to snake_case
- Removed leading/trailing whitespaces
- Standardized city names
- Standardized industry names
- Standardized funding stages
- Removed duplicate records
- Converted funding amount into numeric values
- Converted funding dates into datetime format
- Handled missing values

---

3. Exploratory Data Analysis (EDA)

Performed detailed analysis such as:

- Startup count by city
- Startup count by industry
- Funding distribution
- Funding stage analysis
- Year-wise funding trends
- Investor analysis
- Startup funding tiers
- Funding efficiency calculation
- Startup era classification
- Investor count analysis

---

4. Data Filtering

Applied various filtering techniques including:

- Bengaluru startups with funding greater than ₹100 Cr
- Fintech, EdTech and HealthTech startups
- Startups founded between 2015–2020
- Startup names containing specific keywords

---

5. Feature Engineering

Created new features like:

- Funding Efficiency
- Funding Tier
- Startup Era
- Investor Count

---

6. Aggregation & GroupBy Analysis

Performed:

- Average funding by industry
- Total funding by city
- Average funding per startup
- Highest funded startup in each industry
- Industry-wise startup counts
- Crosstab analysis
- Market saturation analysis

---

📈 Business Insights Generated

The project helps answer important business questions such as:

- Which industries receive the highest funding?
- Which cities attract the most startup investments?
- Which startups have the highest funding efficiency?
- Which industries are growing rapidly?
- Which startup sectors have the highest competition?
- Which emerging startups have strong investment potential?

---

📚 Python & Pandas Concepts Used

- DataFrames
- Series
- Indexing
- loc
- iloc
- apply()
- map()
- replace()
- fillna()
- dropna()
- value_counts()
- groupby()
- agg()
- idxmax()
- sort_values()
- isin()
- between()
- str.contains()
- pd.cut()
- pd.to_datetime()
- pd.to_numeric()
- Crosstab Analysis
- Feature Engineering
- Data Cleaning
- Exploratory Data Analysis (EDA)

---

📁 Repository Structure

├── Week2_Assessment.ipynb
├── indian_startups_funding.csv
├── README.md

---

▶️ How to Run

1. Clone the repository

git clone https://github.com/your-username/your-repository-name.git

2. Navigate to the project folder

cd your-repository-name

3. Install the required libraries

pip install pandas numpy

4. Open the Jupyter Notebook or Google Colab.

5. Run all notebook cells sequentially.

---

🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Real-world data cleaning
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Business data interpretation
- Pandas data manipulation
- Feature engineering
- GroupBy and aggregation techniques
- Writing efficient Python code for data analysis

---

📌 Future Improvements

- Add data visualizations using Matplotlib and Seaborn.
- Build an interactive dashboard using Power BI or Tableau.
- Perform predictive analysis using Machine Learning.
- Deploy the analysis using Streamlit.

---

---

⭐ If you found this project helpful, consider giving this repository a Star!
