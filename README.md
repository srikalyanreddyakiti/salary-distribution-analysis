# 💼 Data Science Salary Analysis Project

This project analyzes salary trends and disparities within the field of data science in California. Using real-world datasets, we explored how job title, company, location, qualifications, and employee benefits influence compensation. The study employs statistical modeling and visualizations to guide professionals and employers in making informed decisions.

---

## 🎯 Objective

To identify key factors that drive salary variations in the data science field and deliver actionable insights for both job seekers and employers.

---

## 📂 Datasets Used

1. **`title_location_company_salary.csv`**  
   - Columns: `Title`, `Location`, `Company`, `Salary`  
   - Insights into how salaries vary by job title, region, and organization.

2. **`qualifications.csv`**  
   - Columns: `Title`, `Qualifications`, `Years of Experience`  
   - Analyzes how education and experience levels affect salaries.

3. **`benefits.csv`**  
   - Columns: `Title`, `Health Insurance`, `Retirement Benefits`, `Stock Options`  
   - Highlights total compensation packages beyond base salary.

4. **`salary.csv`**  
   - Contains consolidated and cleaned salary records.

---

## 🧹 Data Preprocessing

- Removal of extra index columns like `Unnamed: 0`
- Handling missing values via imputation or deletion
- Data type conversions for categorical and numerical consistency
- Text normalization for consistent formatting
- Data integrity checks for duplicates and anomalies

---

## 📊 Exploratory Data Analysis (EDA)

- **KDE Plots**: Visualize salary distributions by title and level
- **Box Plots**: Show spread and outliers across job roles
- **Histograms**: Highlight frequent salary ranges
- **Bar Charts**: Compare job levels and company-wise patterns

---

## 📈 Statistical Modeling

### ✅ Model: Ordinary Least Squares (OLS) Regression
**Equation:**  
`Salary = β₀ + β₁(Job Title) + β₂(Company) + β₃(Location) + β₄(Level) + β₅(Qualifications) + ε`

### 📌 Key Findings:
- **Job Title**: Strong impact on salary (e.g., Senior Data Scientists earn significantly more)
- **Location**: Cities like SF and NYC offer higher pay due to demand and living costs
- **Company**: Reputed firms offer higher compensation
- **Qualifications**: Higher education often leads to higher salaries
- **Level**: Moving from mid to senior level can boost salary by ~20%

### 🔍 Model Performance:
- **R² Score**: 0.96 (excellent explanatory power)
- **F-Statistic**: 14.44 (model is statistically significant)

---

## 💡 Key Insights

- Senior roles show higher salary ranges and more variability
- Entry-level roles are most common, highlighting competitive early stages
- High-tech firms in premium locations dominate the top-paying jobs
- Benefits play a crucial role in total compensation

---

## 🎯 Recommendations

### For Professionals:
- Focus on skill development in high-demand areas
- Target cities and companies with higher compensation history
- Use data insights for strategic job changes and salary negotiations

### For Employers:
- Offer competitive and transparent salary structures
- Invest in employee training and perks
- Use data-driven benchmarks for equitable compensation

---

## 🛠 Technologies Used

- Python 3
- pandas, numpy, matplotlib, seaborn
- statsmodels (for OLS Regression)
- Jupyter Notebook
- Microsoft PowerPoint (for final presentation)

---

## 👥 Contributors

- Sri Kalyan Reddy Akiti  
- Sandeep Kumar Adi  
- Sanjay Kumar Pujari  
---
