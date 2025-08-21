# Data Science Salary Analysis Project

This project analyzes salary trends and disparities within the field of data science in California. Using real-world datasets, we explored how job title, company, location, qualifications, and employee benefits influence compensation. The study employs statistical modeling and visualizations to guide professionals and employers in making informed decisions.

---

## Objective

To identify key factors that drive salary variations in the data science field and deliver actionable insights for both job seekers and employers.

---

## Datasets Used

1. **`title_location_company_salary.csv`**  
   - Columns: `Title`, `Location`, `Company`, `Salary`  
   - Provides insights into how salaries vary by job title, region, and organization.  

2. **`qualifications.csv`**  
   - Columns: `Title`, `Qualifications`, `Years of Experience`  
   - Analyzes how education and experience levels affect salaries.  

3. **`benefits.csv`**  
   - Columns: `Title`, `Health Insurance`, `Retirement Benefits`, `Stock Options`  
   - Highlights compensation packages beyond base salary.  

4. **`salary.csv`**  
   - Contains consolidated and cleaned salary records.  

---

## Data Preprocessing

- Removed unnecessary index columns (e.g., `Unnamed: 0`)  
- Handled missing values via imputation or deletion  
- Converted data types for categorical and numerical consistency  
- Normalized text formatting  
- Checked for duplicates and anomalies  

---

## Exploratory Data Analysis (EDA)

- KDE plots: Salary distributions by title and level  
- Box plots: Spread and outliers across job roles  
- Histograms: Frequent salary ranges  
- Bar charts: Company-wise and job-level comparisons  

---

## Statistical Modeling

### Model: Ordinary Least Squares (OLS) Regression  

**Equation:**  
`Salary = β₀ + β₁(Job Title) + β₂(Company) + β₃(Location) + β₄(Level) + β₅(Qualifications) + ε`  

**Key Findings:**  
- Job Title strongly impacts salary (Senior Data Scientists earn significantly more)  
- Location matters — San Francisco and New York offer the highest salaries  
- Reputed firms provide higher pay scales  
- Qualifications and higher education correlate with higher salaries  
- Moving from mid-level to senior roles increases pay by ~20%  

**Model Performance:**  
- R² Score: 0.96 (strong explanatory power)  
- F-Statistic: 14.44 (statistically significant)  

---

## Key Insights

- Senior roles show higher salaries and greater variability  
- Entry-level positions dominate the market, making competition intense  
- Tech firms in premium cities dominate top-paying roles  
- Benefits significantly influence overall compensation  

---

## Recommendations

**For Professionals:**  
- Build skills in high-demand areas  
- Target locations and firms with higher compensation histories  
- Use insights for salary negotiations and job transitions  

**For Employers:**  
- Maintain competitive salary structures  
- Invest in training and employee benefits  
- Leverage data benchmarks for fair compensation policies  

---

## Technologies Used

- Python 3  
- pandas, numpy, matplotlib, seaborn  
- statsmodels (for OLS Regression)  
- Jupyter Notebook  
- Microsoft PowerPoint (for presentation)  

---

## Contributors

- Sri Kalyan Reddy Akiti  
- Sandeep Kumar Adi  
- Sanjay Kumar Pujari  
