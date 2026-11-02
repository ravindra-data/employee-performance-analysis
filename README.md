# 📊 Employee Performance Analysis

An exploratory data analysis project focused on understanding employee performance, salary distribution, promotion probability, and work-related metrics using Python and statistical techniques.

## 📌 Project Overview

This project analyzes employee data to explore performance patterns, salary distribution, promotion trends, and employee work metrics.

The analysis combines descriptive statistics, probability, distribution analysis, visualization, and linear algebra to derive meaningful insights from employee data.

## 🎯 Objectives

- Analyze employee dataset and identify missing values and duplicates.
- Calculate salary mean, median, and mode.
- Measure variance and standard deviation of completed projects.
- Calculate overall promotion probability.
- Analyze department-wise promotion counts.
- Calculate promotion probability for employees with performance scores above 80.
- Understand salary and performance score distributions.
- Apply statistical techniques to employee data.
- Perform linear algebra operations on employee work vectors.

## 🧰 Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation & Analysis |
| NumPy | Numerical Computations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| SciPy | Statistical Analysis |
| Jupyter Notebook | Interactive Analysis |

## 📁 Project Structure

```text
Employee-Performance-Analysis/
│
├── Employee_performance_analysis.ipynb
├── employee_performance.csv
├── histogram_performance.png
├── salary_distribution.png
├── qqplot_projects.png
├── work_vectors.png
└── README.md
```

## 📈 Analysis Workflow

### 1. Data Loading & Exploration
- Import dataset using Pandas.
- Explore dataset dimensions and data types.
- Check missing values.
- Identify duplicate Employee IDs.
- Generate descriptive statistics.

### 2. Statistical Analysis
- Calculate salary mean, median, and mode.
- Calculate variance of Projects Completed.
- Calculate standard deviation of Projects Completed.
- Analyze salary skewness and kurtosis.

### 3. Probability Analysis
- Calculate overall promotion probability.
- Analyze Department vs Promotion Status.
- Calculate conditional promotion probability for employees with Performance Score > 80.

### 4. Data Visualization
- Performance Score Histogram with Gaussian Curve.
- Salary Distribution using KDE.
- Salary Mean and Median Comparison.
- Q-Q Plot for Projects Completed.
- Employee Work Vectors Visualization.

### 5. Linear Algebra
- Create employee work vectors using Projects Completed and Working Hours.
- Calculate Dot Product.
- Calculate L1 and L2 Norms.
- Calculate Cosine Similarity.
- Calculate Angle Between Work Vectors.

## 📊 Visualizations

| Visualization | Description |
|---|---|
| Performance Histogram | Distribution of employee performance scores |
| Salary Distribution | Salary distribution with KDE, mean, and median |
| Q-Q Plot | Normality assessment of completed projects |
| Work Vectors | Visualization of employee work metrics |

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/<your-username>/Employee-Performance-Analysis.git
```

### 2. Navigate to Project Directory

```bash
cd Employee-Performance-Analysis
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scipy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open `Employee_performance_analysis.ipynb` and execute the cells sequentially.

## 🗂️ Dataset

The project uses an employee performance dataset containing information such as:

- Employee_ID
- Department
- Salary
- Projects_Completed
- Working_Hours
- Performance_Score
- Promotion_Status

**Note:** Ensure that `employee_performance.csv` is placed in the project directory before running the notebook.

## 💡 Key Learning Outcomes

- Data cleaning and preprocessing using Pandas.
- Statistical analysis using NumPy and SciPy.
- Probability calculations using employee data.
- Data visualization using Matplotlib and Seaborn.
- Understanding distributions, skewness, and kurtosis.
- Applying linear algebra concepts to real-world datasets.

---
