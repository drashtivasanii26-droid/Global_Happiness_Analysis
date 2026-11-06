# 🌍 Global Happiness Report Analysis

---

## 👩‍💻 Author

**Drashti Vasani**

---

## 📑 Table of Contents

1. [📌 Project Overview](#-project-overview)
2. [🎯 Project Objectives](#-project-objectives)
3. [🛠️ Tools and Libraries](#️-tools-and-libraries)
4. [📂 Dataset Information](#-dataset-information)
5. [⚙️ Project Workflow](#️-project-workflow)
6. [📊 Sample Output](#-sample-output)
7. [📁 Project Structure](#-project-structure)
8. [📈 Data Visualizations](#-data-visualizations)
9. [🚀 How to Run](#-how-to-run)
10. [📝 Conclusion](#-conclusion)

---

## 📌 Project Overview

The **Global Happiness Report Analysis** project analyzes World Happiness Report data to understand happiness levels across different countries and years.

The project explores the relationship between happiness scores and important factors such as:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Positive affect
- Negative affect

Using Python data analysis and visualization libraries, this project performs data cleaning, statistical analysis, correlation analysis, country-wise and year-wise comparisons, and happiness category classification.

Different charts and visualizations are used to identify patterns and understand the factors associated with happiness.

---

## 🎯 Project Objectives

- Load and explore the World Happiness Report dataset.
- Identify and handle missing values.
- Check and remove duplicate records.
- Generate descriptive statistical summaries.
- Analyze happiness scores across different countries.
- Compare happiness levels across different years.
- Study the relationship between happiness and GDP per capita.
- Analyze the impact of social support and healthy life expectancy.
- Perform correlation analysis among numerical variables.
- Classify countries into High, Medium, and Low Happiness categories.
- Visualize data patterns using different charts.

---

## 🛠️ Tools and Libraries

| Tool / Library | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data loading, cleaning, grouping, and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization and regression plots |
| Jupyter Notebook | Writing and executing Python code |

---

## 📂 Dataset Information

**Dataset:** World Happiness Report Dataset

**File Name:** `World_Happiness_Report_full.csv`

The dataset contains information about happiness scores and several factors related to happiness across different countries and years.

### Important Dataset Columns

- Country name
- year
- Life Ladder
- Log GDP per capita
- Social support
- Healthy life expectancy at birth
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Positive affect
- Negative affect

### Loading Dataset

```python
df = pd.read_csv("Dataset/World_Happiness_Report_full.csv")
```

Place the CSV file inside a folder named `Dataset` so that the notebook can load it using the path above.

---

## ⚙️ Project Workflow

### 1. Import Libraries

Imports the required Python libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn

### 2. Load and Explore Dataset

- Loads the World Happiness Report CSV dataset.
- Displays the first and last records using `head()` and `tail()`.
- Checks dataset shape and information.
- Identifies missing values.
- Checks duplicate records.

### 3. Data Cleaning

- Handles missing numerical values using the median.
- Handles missing categorical values using the mode.
- Removes duplicate records.
- Prepares the dataset for further analysis.

### 4. Descriptive Statistics

Generates statistical summaries to understand the distribution of numerical data, including:

- Life Ladder
- Healthy life expectancy at birth
- Social support
- Other numerical variables

### 5. Correlation Analysis

Calculates the correlation between numerical variables to understand their relationships.

A Seaborn heatmap is used to display the correlation matrix visually.

### 6. Country-wise and Year-wise Analysis

- Analyzes average happiness scores by country.
- Compares happiness scores across different years.
- Identifies countries with higher and lower happiness scores.
- Displays country-wise and year-wise comparisons using charts.

### 7. Happiness Category Classification

Classifies countries into three categories:

- High Happiness
- Medium Happiness
- Low Happiness

The classification is based on average happiness and average social support.

**Classification Conditions:**

- High Happiness: Average Happiness ≥ 7 and Average Social Support ≥ 0.75.
- Medium Happiness: Average Happiness ≥ 5.
- Low Happiness: Countries that do not satisfy the above conditions.

The project also displays the number of countries in each happiness category.

### 8. Yearly Happiness Category Analysis

- Maps each country's happiness category to its dataset records.
- Calculates the percentage share of Low, Medium, and High Happiness categories for each year.
- Displays the results using a stacked bar chart.

### 9. Relationship Analysis

Studies the relationship between happiness and important factors such as:

- GDP per capita vs Happiness
- Social support vs Happiness
- Healthy life expectancy vs Happiness

Scatter plots and regression plots are used to visualize these relationships.

---

## 📊 Sample Output

The notebook generates the following outputs:

- Dataset preview using `head()` and `tail()`.
- Dataset information and shape.
- Missing-value and duplicate checks.
- Descriptive statistical summary.
- Correlation matrix.
- Happiness category counts.
- Country-wise happiness analysis.
- Year-wise happiness analysis.
- Yearly happiness category percentage share.
- Scatter plots and regression plots.

Run all notebook cells to generate the actual outputs and visualizations.

---

## 📁 Project Structure

```text
Global-Happiness-Report-Analysis/
│
├── Dataset/
│   └── World_Happiness_Report_full.csv
│
├── Global_Happiness_Analysis.ipynb
│
└── README.md
```

---

## 📈 Data Visualizations

The project includes the following visualizations:

1. **Correlation Heatmap** – Shows correlations between numerical variables.
2. **Country-wise Happiness Bar Chart** – Compares happiness scores across countries.
3. **Year-wise Happiness Line Chart** – Shows happiness trends over different years.
4. **Year-wise Happiness Bar Chart** – Compares happiness scores by year.
5. **GDP vs Happiness Scatter Plot** – Shows the relationship between GDP per capita and happiness.
6. **Social Support vs Happiness Scatter Plot** – Shows the relationship between social support and happiness.
7. **Regression Plots** – Visualize relationships between happiness and GDP, social support, and healthy life expectancy.
8. **Yearly Happiness Category Stacked Bar Chart** – Displays the percentage share of Low, Medium, and High Happiness categories across years.
9. **Happiness Category Scatter Plot** – Shows the relationship between average social support and average happiness for different categories.

---

## 🚀 How to Run

### 1. Install Required Libraries

Open the terminal and run:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 2. Open Jupyter Notebook

Open the project folder in VS Code or Jupyter Notebook.

### 3. Load the Dataset

Make sure the CSV file is placed inside the `Dataset` folder.

### 4. Run the Project

Open `Global_Happiness_Analysis.ipynb` and execute all cells using **Run All**.

---

## 📝 Conclusion

The Global Happiness Report Analysis project provides insights into happiness levels across different countries and years.

Through data cleaning, descriptive statistics, correlation analysis, happiness category classification, and data visualization, the project explores the relationship between happiness and factors such as GDP per capita, social support, and healthy life expectancy.

This project demonstrates how Python libraries like Pandas, NumPy, Matplotlib, and Seaborn can be used to analyze real-world datasets and present meaningful insights through visualizations.

---

## ✨ **Thank You!**