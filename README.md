# 📊 Data Analyst Portfolio — Python

> A collection of **7 end-to-end data analysis projects** spanning retail, e-commerce, healthcare, and classic datasets. Each project demonstrates real-world EDA workflows: ingestion → cleaning → filtering → grouping → visualization → insight.

---

## 👤 About

This portfolio was built to showcase practical data analysis skills using Python. Projects cover a wide range of domains and datasets, each following a structured analytical approach to extract meaningful, actionable insights.

---

## 📂 Projects

### 1. ☕ Coffee Sales Project
**File:** `Coffee Sales Project/Coffee_Sales_Project.ipynb`  
**Dataset:** `Coffe_sales.csv`

Analyzes coffee shop sales patterns across time-of-day, weekday, and product type.

**Key Analysis:**
- Most popular coffee types by time of day (Morning / Night)
- Monthly and weekly sales trends
- Revenue breakdown by coffee type and price point
- Visualizations: pie charts (time-of-day share, coffee type distribution), bar plots (weekday vs. coffee type), histogram distributions

**Insight:** Latte and Americano with Milk are the top-selling items, with peak demand concentrated in the morning. Weekday patterns reveal consistent mid-week highs.

---

### 2. 🛒 Amazon Sales Report Project
**File:** `Amazon Sales Report Project/Project_Of_Amazon_Sales_Report.ipynb`

Performs deep EDA on Amazon India sales data covering order fulfilment, shipping, promotions, and category demand.

**Key Analysis:**
- Missing value handling across 10+ columns (courier status, currency, ship city/state, postal code, promotion IDs)
- Category-level sales by city and state
- Highest-demand product categories per city
- Grouping by fulfillment method, B2B vs. B2C, sales channel, and courier status
- Visualizations: bar plots (Category vs. Amount, Status vs. Amount), distribution charts

**Insight:** Western Dress shows concentrated demand in specific metro cities. Merchant fulfilment dominates over Amazon fulfilment in certain segments.

---

### 3. 🛍️ Ecommerce Customers Project
**File:** `Ecommerce Customers Project/Project Of Ecommerce Customer (1).ipynb`  
**Dataset:** `Ecommerce Customers.xlsx`

Explores customer behavior metrics and their impact on annual spending for an online retail platform.

**Key Analysis:**
- Session length, time on app vs. website, membership duration
- Scatter analysis: Length of Membership vs. Yearly Amount Spent
- App time vs. website time comparison
- Avg. Session Length distributions (histogram + KDE)
- Grouping by avatar type, email, and address segments

**Insight:** Membership tenure is the strongest predictor of annual spend. App engagement drives more revenue than website engagement — a signal for mobile-first investment.

---

### 4. 🏥 Healthcare Stroke Project
**File:** `Healthcare Stroke Project/Healthcare_Project.ipynb`  
**Dataset:** `healthcare-dataset-stroke-data.csv`

Investigates stroke risk factors including hypertension, BMI, glucose levels, smoking, and lifestyle attributes.

**Key Analysis:**
- BMI null-value imputation using column mean
- Stroke incidence grouped by gender, smoking status, marital status, and residence type
- Hypertension analysis by age and gender
- Grouping: work type vs. residence, marriage vs. employment
- Visualizations: pie charts (gender, work type, residence, marital status, smoking status), scatter plots (BMI vs. age, BMI vs. glucose, hypertension vs. age, stroke vs. age), histogram (glucose level distribution)

**Insight:** Private-sector employees constitute ~57% of the dataset. Hypertension is the most significant stroke risk factor, particularly among older individuals.

---

### 5. 🚢 Titanic Project
**File:** `Titanic Project/Titanic Project.ipynb`  
**Dataset:** `Titanic-Dataset.xls`

Classic survival analysis with a focus on data cleaning fundamentals, filtering, and visualization.

**Key Analysis:**
- Missing value treatment: Age (mean imputation), Cabin (mode fill), Embarked (row drop)
- Filtering: male passengers under 18, class-wise passenger counts
- Groupby: gender × class, gender × survival, gender × parents/children × survival
- Duplicate handling and column dropping
- Visualizations: pie charts (gender, passenger class), bar charts (embarkation port, siblings/spouse), histogram (age, ticket fare)

**Insight:** Gender was a decisive factor — female passengers had significantly higher survival rates across all classes. Third-class male passengers had the lowest survival probability.

---

### 6. 🏪 Sample Superstore Project
**File:** `Sample Store Project/Sample_Superstore_Project.ipynb`  
**Dataset:** `Sample - Superstore.xls`

Business performance analysis for a US retail superstore across categories, regions, states, and customer segments.

**Key Analysis:**
- Statistical summaries (mean, sum, min, max, std) for Sales and Profit by Category and Sub-Category
- Top states and cities by order volume and profit
- Regional profit and sales comparison (East, West, Central, South)
- Segment and ship-mode breakdown by sub-category
- Visualizations: bar plots (Sales vs. Category, Sales vs. State), pie chart (Region distribution), grouped bar charts

**Insight:** Technology drives the highest average sales, while Furniture struggles with profitability. The West region leads in both sales and profit; certain sub-categories like Tables consistently generate losses.

---

### 7. 😴 Sleep Health & Lifestyle Project
**File:** `Sleep_health_and_lifestyle Project/Project_of_Sleep_health_and_lifestyle.ipynb`  
**Dataset:** `Sleep_health_and_lifestyle_dataset.csv`

Examines the relationship between sleep quality, lifestyle choices, occupational stress, physical activity, and health outcomes.

**Key Analysis — structured as research questions:**

**Health & Sleep Analysis**
- Q1: People sleeping <6 hours with high stress (>7) — burnout risk identification
- Q2: Overweight/obese individuals with sleep disorders — obesity–sleep correlation
- Q3: Occupations with highest sleep disorder incidence — workplace wellness targeting
- Q4: Adults 40+ sleeping <7 hours — aging population sleep risk

**Lifestyle & Fitness Analysis**
- Q5: 10,000+ daily steps vs. sleep quality improvement
- Q6: Low physical activity (<30 min) + high BMI — lifestyle disease risk
- Q7: Average sleep quality for 60+ min daily exercisers

**Medical Risk Analysis**
- Hypertension, cardiovascular risk, and stress-level correlations

**Insight:** Nurses and doctors show the highest sleep disorder rates. Regular walkers (10k+ steps) report measurably better sleep quality scores.

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading, cleaning, filtering, grouping |
| NumPy | Numerical operations and imputation |
| Matplotlib | Base plotting (pie, bar, hist, scatter) |
| Seaborn | Statistical visualization (barplot, displot, relplot, histplot) |
| Jupyter Notebook | Interactive development environment |
| Google Colab | Cloud execution (some notebooks) |

---

## 📁 Repository Structure

```
Data-Analyst-Portfolio-Using-Python/
│
├── Amazon Sales Report Project/
│   └── Project_Of_Amazon_Sales_Report.ipynb
│
├── Coffee Sales Project/
│   ├── Coffe_sales.csv
│   └── Coffee_Sales_Project.ipynb
│
├── Ecommerce Customers Project/
│   ├── Ecommerce Customers.xlsx
│   └── Project Of Ecommerce Customer.ipynb
│
├── Healthcare Stroke Project/
│   ├── healthcare-dataset-stroke-data.csv
│   └── Healthcare_Project.ipynb
│
├── Sample Store Project/
│   ├── Sample - Superstore.xls
│   └── Sample_Superstore_Project.ipynb
│
├── Sleep_health_and_lifestyle Project/
│   ├── Sleep_health_and_lifestyle_dataset.csv
│   └── Project_of_Sleep_health_and_lifestyle.ipynb
│
├── Titanic Project/
│   ├── Titanic-Dataset.xls
│   └── Titanic Project.ipynb
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Muhammad-Musharraf/Data-Analyst-Portfolio-Using-Python.git
cd Data-Analyst-Portfolio-Using-Python
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn openpyxl xlrd
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

Open any `.ipynb` file from the project folders to explore the analysis.

> **Note:** Some notebooks were originally developed in Google Colab and reference Google Drive paths. To run them locally, update the file paths to point to the local dataset files included in each project folder.

---

## 🔍 Core EDA Workflow

Every project follows this structured pipeline:

```
1. Import Libraries       → pandas, numpy, matplotlib, seaborn
2. Load Dataset           → read_csv / read_excel
3. Explore Data           → .head(), .info(), .describe(), .shape
4. Clean Data             → Handle nulls (fillna / dropna), remove duplicates
5. Filter Data            → Boolean masking, conditional queries
6. Group & Aggregate      → groupby(), value_counts(), agg()
7. Visualize              → Bar plots, pie charts, scatter plots, histograms, KDE
8. Generate Insights      → Written summary of findings
```

---

## 🎯 Skills Demonstrated

- Data ingestion from CSV and Excel formats
- Null value treatment (mean, median, mode imputation; conditional fill; row removal)
- Boolean filtering and multi-condition masking
- Groupby aggregations across multiple dimensions
- Statistical summarization (mean, std, min, max, sum)
- Data visualization and storytelling
- Insight generation from real-world datasets

---

## 📄 License

This repository is created for educational and portfolio purposes. Datasets used are publicly available (Kaggle and open-data sources).

---

## 🤝 Connect

Feel free to fork this repository, raise issues, or submit pull requests with improvements.  
⭐ Star the repo if you find it useful!


