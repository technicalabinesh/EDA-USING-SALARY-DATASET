# 📊 EDA Using Salary Dataset

An Exploratory Data Analysis (EDA) project that uncovers salary trends, pay distributions, and factors influencing compensation across various job roles, cities, and companies in India.

---

## 📁 Repository Structure

```
EDA-USING-SALARY-DATASET/
├── Project+14+-+Salary+Data+Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── Salary_Dataset_DataScienceLovers.csv       # Raw salary dataset (22,000+ records)
└── README.md
```

---

## 📌 Dataset Overview

The dataset (`Salary_Dataset_DataScienceLovers.csv`) contains real-world salary information collected from multiple companies across different locations, job roles, and employment types.

| Column | Description |
|---|---|
| `Rating` | Company rating (1–5 scale) |
| `Company Name` | Name of the employer |
| `Job Title` | Specific job title of the employee |
| `Salary` | Annual salary (in INR) |
| `Salaries Reported` | Number of employees who reported this salary |
| `Location` | City of the job |
| `Employment Status` | Full Time / Intern / Contractor / Trainee |
| `Job Roles` | Broad job role category |

**Total Records:** 22,770+  
**Job Roles:** Android, Backend, Frontend, Database, IOS, Java, Mobile, Python, SDE, Testing, Web  
**Employment Types:** Full Time, Intern, Contractor, Trainee  

---

## 🔍 Analysis Steps

### 1️⃣ Import Libraries
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualizations

### 2️⃣ Load Dataset
- Load CSV into a Pandas DataFrame

### 3️⃣ Basic Dataset Understanding
- Shape, data types, summary statistics (`df.describe()`)

### 4️⃣ Data Cleaning
- Check and handle missing values
- Remove duplicate rows

### 5️⃣ Outlier Detection & Removal
- Boxplot visualization of salary distribution
- IQR (Interquartile Range) method to filter outliers

### 6️⃣ Univariate Analysis
- Salary distribution using histogram + KDE plot

### 7️⃣ Answering Business Questions

| # | Question |
|---|---|
| Q1 | Which job roles have the highest average salary? |
| Q2 | Which cities offer the highest average salary? |
| Q3 | Top 5 companies in New Delhi with a rating of 5, by highest & lowest salary |
| Q4 | Which job title has the highest number of salaries reported? |
| Q5 | Top 10 companies with the highest average salary (min. 20 reports) |
| Q6 | Is there a relationship between company rating and salary? |
| Q7 | Does employment status affect salary? |
| Q8 | Which job roles are most common? |
| Q9 | How does average salary change as company rating increases? |

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive development environment

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/technicalabinesh/EDA-USING-SALARY-DATASET.git
   cd EDA-USING-SALARY-DATASET
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook "Project+14+-+Salary+Data+Analysis.ipynb"
   ```

---

## 📈 Key Insights

- Salary distribution is right-skewed, with most salaries clustered in the lower-to-mid range.
- Certain job roles (e.g., SDE, Python, Backend) tend to command higher average salaries.
- Metro cities generally offer higher compensation compared to smaller locations.
- Higher company ratings do not always strongly correlate with higher salaries.
- Full-time employees earn significantly more than interns, trainees, and contractors.

---

## 📄 License

This project is intended for educational and portfolio purposes.