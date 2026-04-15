# 📊 EDA Using Salary Dataset

A comprehensive **Exploratory Data Analysis (EDA)** project on a real-world salary dataset containing 22,000+ records from various companies, job roles, and locations across India.

---

## 📁 Repository Structure

```
EDA-USING-SALARY-DATASET/
├── Project+14+-+Salary+Data+Analysis.ipynb   # Main Jupyter Notebook
├── Salary_Dataset_DataScienceLovers.csv       # Dataset
└── README.md
```

---

## 📌 Dataset Overview

The dataset (`Salary_Dataset_DataScienceLovers.csv`) contains real-world salary information with the following columns:

| Column | Description |
|---|---|
| `Rating` | Company rating (out of 5) |
| `Company Name` | Name of the company |
| `Job Title` | Job title of the employee |
| `Salary` | Annual salary (in INR) |
| `Salaries Reported` | Number of salary reports for that role |
| `Location` | City/location of the job |
| `Employment Status` | Full Time / Part Time / Contract, etc. |
| `Job Roles` | Broad job role category |

---

## 🔍 Analysis Questions Answered

1. What does the salary distribution look like?
2. Which job roles have the highest average salary?
3. Which cities offer the highest average salary?
4. Top 5 companies offering the highest average salary?
5. Top 5 companies with salaries reported more than 20 times?
6. Is there a relationship between company rating and salary?
7. Does employment status affect salary?
8. Which job roles are most common?
9. How does average salary change as company rating increases?

---

## 🛠️ Steps Performed

### 1. Import Libraries
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization

### 2. Load Dataset
- Loaded the CSV file into a pandas DataFrame

### 3. Basic Dataset Understanding
- Shape, data types, summary statistics

### 4. Data Cleaning
- Checked and handled missing values
- Removed duplicate rows

### 5. Outlier Detection & Removal
- Visualized salary outliers using box plots
- Applied the **IQR (Interquartile Range)** method to filter extreme values

### 6. Exploratory Data Analysis (EDA)
- Salary distribution histogram
- Top-paying job roles (bar chart)
- Top-paying cities (bar chart)
- Top companies by average salary
- High-reporting companies analysis
- Correlation between rating and salary (scatter + regression plot)
- Employment status vs. salary (box plot)
- Most common job roles (horizontal bar chart)
- Salary trend across company ratings (line plot)
- **Mini Dashboard** summarizing key insights

---

## 📊 Visualizations

The notebook includes:
- 📦 Box plots (outlier detection, employment status vs salary)
- 📈 Bar & horizontal bar charts (job roles, locations, companies)
- 🔵 Scatter plots with trend lines (rating vs salary)
- 📉 Line plots (salary trend by rating)
- 🗂️ Multi-panel mini dashboard

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Notebook

```bash
jupyter notebook "Project+14+-+Salary+Data+Analysis.ipynb"
```

> **Note:** Update the dataset file path in the notebook's data-loading cell to match your local directory.

---

## 🧰 Technologies Used

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Pandas | Data manipulation & analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive development environment |

---

## 👤 Author

**Rohit Grewal** – Sr. Data Analyst  
*Part of the Data Science Lovers series*
