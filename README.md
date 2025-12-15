# Telecom Customer Churn Analysis: Exploratory Data Analysis

> An in-depth exploratory data analysis (EDA) project investigating customer churn patterns in the telecom industry, with actionable insights for customer retention strategies.

---

## 📊 Project Overview

This project performs a comprehensive exploratory data analysis on telecom customer churn data to identify key drivers of customer attrition, segment customers by churn risk, and uncover behavioral patterns that correlate with churn. The analysis leverages Python data science tools to provide business-ready insights for retention strategy optimization.

**Objective:** Understand *why* customers leave and identify *which* customer segments are most at risk of churn.

---

## 📁 Dataset

**File:** `Customer Churn.csv`

**Key Attributes:**
- **Demographics:** Age, gender, location insights
- **Account Information:** Contract type, tenure, total charges, monthly charges
- **Service Subscriptions:** Internet service, phone service, streaming, security, backup services
- **Target Variable:** Churn (binary: Yes/No)

**Size & Scope:** Multi-feature telecom customer dataset enabling univariate and bivariate analysis of churn determinants.

---

## 🔍 Analysis Methodology

The exploratory data analysis follows a structured workflow:

1. **Data Exploration:** Examine dataset structure, data types, and summary statistics
2. **Data Quality Assessment:** Identify missing values, duplicates, and data inconsistencies
3. **Univariate Analysis:** Analyze individual feature distributions for churned vs. non-churned customers
4. **Bivariate Analysis:** Investigate relationships between features and churn behavior
5. **Pattern Recognition:** Identify key churn drivers and high-risk customer segments
6. **Visualization:** Create compelling charts and plots to communicate insights

---

## 💡 Key Findings

The analysis reveals critical churn patterns:

- **Contract Type Impact:** Month-to-month contracts show significantly higher churn rates compared to annual or two-year contracts
- **Service Bundles:** Customers with limited service subscriptions exhibit higher churn propensity
- **Tenure Effect:** Newer customers (low tenure) are at elevated churn risk
- **Pricing Sensitivity:** High monthly charges correlate with increased churn in certain segments
- **High-Risk Segments:** Identified specific customer profiles requiring targeted retention efforts

*For detailed findings and visualizations, see the project notebook and report.*

---

## 📂 Project Structure

```
├── TCA.ipynb                              # Main Jupyter Notebook with complete EDA workflow
├── Customer Churn.csv                     # Raw dataset (telecom customer records)
├── TELCO CHURN ANALYSIS- Google Docs.pdf  # Executive summary and insights report
├── anaconda_projects/db                   # Project environment directory
└── README.md                              # This file
```

### File Descriptions

| File | Purpose |
|------|----------|
| `TCA.ipynb` | Comprehensive EDA notebook containing data loading, cleaning, exploratory analysis, statistical tests, and visualizations |
| `Customer Churn.csv` | Raw telecom customer dataset with 7,000+ records |
| `TELCO CHURN ANALYSIS- Google Docs.pdf` | Executive report summarizing key insights and business recommendations |

---

## 🛠️ Technologies & Libraries

**Environment:** Python 3.x | Jupyter Notebook | Anaconda

**Key Libraries:**
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Statistical Analysis:** `scipy`, `scikit-learn`
- **Data Quality:** Data cleaning and validation techniques

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Anaconda or pip package manager
- Jupyter Notebook

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/surag29/CUSTOMER-CHURN-ANALYSIS-EDA-PROJECT.git
   cd CUSTOMER-CHURN-ANALYSIS-EDA-PROJECT
   ```

2. **Install required libraries:**
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
   ```
   Or use the Anaconda environment:
   ```bash
   conda env create -f environment.yml
   conda activate churn-analysis
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open and run `TCA.ipynb`:**
   - Navigate to the notebook in your browser
   - Execute cells sequentially to explore the analysis
   - Review outputs, visualizations, and statistical findings

---

## 📈 Analysis Highlights

- **Exploratory Visualizations:** Distribution plots, correlation matrices, and segment comparisons
- **Statistical Testing:** Hypothesis testing to validate churn patterns
- **Segment Analysis:** Customer segmentation by contract type, tenure, and service adoption
- **Actionable Insights:** Recommendations for retention strategy and customer lifecycle management

---

## 💼 Business Applications

This analysis supports:

✓ **Retention Strategy Development:** Identify and target high-risk customer segments  
✓ **Pricing Optimization:** Understand price sensitivity and willingness-to-pay dynamics  
✓ **Service Bundling:** Design attractive service packages to reduce churn  
✓ **Customer Experience:** Improve satisfaction in at-risk segments  
✓ **Predictive Modeling:** Foundation for building churn prediction models  

---

## 📊 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Statistical Analysis & Hypothesis Testing
- Data Visualization & Communication
- Business Insight Generation
- Customer Segmentation
- Python Programming (pandas, matplotlib, seaborn)
- Jupyter Notebook Development

---

## 🔗 Resources & References

- **Dataset Source:** Telecom customer churn data
- **Analysis Notebook:** `TCA.ipynb` (comprehensive methodology and code)
- **Executive Report:** `TELCO CHURN ANALYSIS- Google Docs.pdf`

---

## 📝 Author

**Surag29** | Data Analyst | Portfolio Project

---

## 📄 License

This project is open source and available for educational and portfolio purposes.

---

## 🤝 Contributing

Feedback and suggestions are welcome! Feel free to open issues or submit pull requests with improvements.

---

*Last Updated: December 2025*
