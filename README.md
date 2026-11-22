# Retail Sales Promotion Analysis

## Project Overview

Retail businesses use promotional strategies such as discounts and special offers to increase sales and attract customers. However, not every promotion produces the same results.

This project analyzes retail sales data to understand the impact of promotions on sales performance. It uses Exploratory Data Analysis (EDA), statistical hypothesis testing, bootstrap analysis, regression, and classification techniques to evaluate promotional effectiveness and identify opportunities for better targeting.

## Objectives

- Analyze retail sales data and identify important sales patterns.
- Understand the relationship between promotions and sales performance.
- Compare sales during promotional and non-promotional periods.
- Apply statistical tests to evaluate the significance of promotional effects.
- Use regression analysis to study factors influencing sales.
- Build a classification model for promotion-related targeting.
- Evaluate model performance and analyze targeting effectiveness.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy, Bootstrap Analysis
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook, VS Code
- **Version Control:** Git and GitHub

## Project Structure

```text
Retail_Sales_Promotion_Project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── store.csv
│   └── sample_submission.csv
│
├── figures/
│   ├── bootstrap_distribution.png
│   ├── confusion_matrix.png
│   ├── lift_curve.png
│   ├── promotion_boxplot.png
│   ├── monthly_sales_trend.png
│   └── other visualizations
│
├── notebooks/
│   └── retail_sales_promotion.ipynb
│
├── outputs/
│   ├── analysis_dataset.csv
│   ├── bootstrap_results.csv
│   ├── classification_metrics.csv
│   ├── ttest_results.csv
│   ├── regression_diagnostics.csv
│   └── other analysis results
│
├── .gitignore
└── README.md
```

## Methodology

### 1. Data Collection and Preprocessing
- Loaded retail sales datasets.
- Examined dataset structure, columns, and data types.
- Handled missing values and prepared data for analysis.
- Combined relevant datasets for further analysis.

### 2. Exploratory Data Analysis (EDA)
- Analyzed sales distribution and trends.
- Studied sales patterns across different days and months.
- Compared promotional and non-promotional sales.
- Created visualizations to understand business patterns.

### 3. Statistical Analysis
- Applied hypothesis testing to evaluate differences in sales.
- Used t-tests to examine promotional sales differences.
- Performed bootstrap analysis to understand the distribution and reliability of estimated effects.

### 4. Regression Analysis
- Developed regression analysis to study the relationship between relevant variables and sales.
- Evaluated model performance using regression diagnostics.
- Examined residuals and influential observations.

### 5. Classification and Targeting
- Applied classification techniques to analyze promotion-related outcomes.
- Evaluated the model using classification performance metrics.
- Generated targeting predictions and examined model effectiveness using lift analysis.

## Key Analysis Outputs

The project generates the following outputs:

- Sales trend visualizations.
- Promotion versus non-promotion comparisons.
- Bootstrap distribution and statistical results.
- Hypothesis testing results.
- Regression diagnostics.
- Classification performance metrics.
- Confusion matrix and lift curve.
- Promotion targeting predictions.

Detailed results are available in the `outputs/` and `figures/` folders.

## How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/vaishnavibijjur/Retail-Sales-Promotion.git
```

**Step 2: Navigate to the project folder**

```bash
cd Retail-Sales-Promotion
```

**Step 3: Create a virtual environment**

```bash
python -m venv .venv
```

**Step 4: Activate the virtual environment**

For Windows:

```bash
.venv\Scripts\activate
```

**Step 5: Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels jupyter
```

**Step 6: Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `notebooks/retail_sales_promotion.ipynb` and run the cells.

## Skills Demonstrated

- Python Programming
- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Statistical Hypothesis Testing
- Bootstrap Analysis
- Regression Analysis
- Classification
- Model Evaluation
- Business and Sales Data Analysis

## Conclusion

This project demonstrates how data analytics and machine learning techniques can be applied to retail sales data to evaluate promotional effectiveness.

By combining exploratory analysis, statistical testing, regression, and classification, the project provides insights that can support data-driven promotional planning and business decision-making.

## Author

**Vaishnavi Bijjur**

Data Science Engineering Student | Aspiring Data Analyst

[GitHub Profile](https://github.com/vaishnavibijjur)
