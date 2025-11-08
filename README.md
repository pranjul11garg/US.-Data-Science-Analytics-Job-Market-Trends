# 📊 US Data Science & Analytics Job Market Trends Analysis

[![Website](https://img.shields.io/badge/Website-Live-brightgreen)](https://pranjul11garg.github.io/US.-Data-Science-Analytics-Job-Market-Trends/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)

## 📖 Project Overview

This project analyzes real-world job posting data from Lightcast to identify emerging trends in data science, business analytics, and machine learning careers. Using advanced analytics and machine learning techniques, we provide actionable insights into salary patterns, skill requirements, geographic demand, and industry-specific hiring trends.

**🔗 [View Interactive Report](https://pranjul11garg.github.io/US.-Data-Science-Analytics-Job-Market-Trends/)**


## 🚀 Key Highlights: Business Impact

**100K+ job postings** analyzed across 50 US states and 10+ industries  
**79% prediction accuracy** achieved in ML/Data Science role classification using Random Forest  
**4 distinct career clusters** identified through K-Means clustering (junior, specialized, entry-level, senior professionals)  
**Geographic insights** revealing Texas (8,050 jobs) and California (7,000 jobs) as top hiring states

### 💡 Key Findings

**SQL, Python, and Machine Learning** dominate as top 3 required skills (25K+ postings each)  
**86% correlation** between higher education levels (Master's/Ph.D.) and analytics roles in Tech & Finance  
**Professional & Technical Services** sector accounts for 7,620 analytics positions (highest demand)  
**AI/ML skills** now explicitly required in 60% of 2025 job postings vs. previous years

## 🛠️ Technical Stack

**Category** | **Technologies**
---|---
**Languages** | Python, SQL
**Data Processing** | Pandas, NumPy, PySpark
**Machine Learning** | Scikit-learn (Random Forest, K-Means, Linear Regression)
**NLP** | TF-IDF Vectorization, Text Mining
**Visualization** | Plotly, Matplotlib, Seaborn, Quarto
**Database** | MySQL, Parquet
**Deployment** | GitHub Pages, Quarto Website

---

## 📊 Analysis Modules

### 📋 1. Data Cleaning & Preprocessing

Handled missing values using correlation-based imputation strategies  
Normalized skill fields and removed duplicates  
Created structured columns for salary, experience, education, and skills  
**Result:** Clean dataset with 23 key features ready for analysis

### 📈 2. Exploratory Data Analysis

**Industry Trends**  
- Tech & Services leads with 7,620 analytics roles
- Finance sector shows 4,246 analytics positions (42% of total postings)
- Education sector has highest analytics concentration (73% of roles)

**Geographic Distribution**  
- Interactive choropleth map reveals state-by-state demand
- Texas, California, and New York dominate hiring (combined 19K+ jobs)
- Wyoming has lowest demand (103 jobs)

**Skill Requirements**  
- SQL appears in 25K+ job postings (top technical skill)
- Python programming required in 12K+ analytics roles
- Business Intelligence & Dashboard tools in 10K+ postings

### 🤖 3. Machine Learning Models

**Random Forest Classification (79% Accuracy)**  
- **Goal:** Predict whether job requires ML/Data Science expertise
- **Features:** Job title, industry (NAICS), education, experience + TF-IDF of job descriptions
- **Key Insight:** Job title alone accounts for 60% of predictive power; adding text data improved accuracy from 74% to 79%

**K-Means Clustering (4 Clusters)**  
- **Cluster 0:** Junior roles (<$150K, 2-5 years experience)
- **Cluster 1:** High-paying specialists ($100K-$500K, ~3 years) – fast-track promotions
- **Cluster 2:** Entry-level (<$100K, 0-4 years)
- **Cluster 3:** Senior professionals (<$200K, 6-13 years)

**Multiple Linear Regression (R² = 0.98)**  
- **Target:** Predict salary from years of experience
- **Result:** Strong linear relationship – experience is reliable salary predictor
- **MSE:** 2,450,000 (indicates tight fit around actual salaries)

### 🎯 4. Skill Gap Analysis

Compared team skills against market demand using TF-IDF frequency analysis  
**Strengths:** Communication, SQL, Excel  
**Gaps:** Machine Learning, Cloud Computing, PySpark, Data Visualization  
**Recommendation:** Prioritize upskilling in AI/ML and cloud platforms (AWS/Azure)

---

## 🎓 Insights for Career Planning

### For Recent Graduates

✅ **SQL + Python + ML** form the minimum skill foundation  
✅ Bachelor's degree sufficient for entry; Master's advantageous for Tech/Finance  
✅ Target **Texas, California, New York** for maximum opportunities  
✅ Focus on **Professional Services, Info Tech, Finance** industries

### For Career Switchers

✅ **AI/ML skills** now expected in 60% of analytics roles (up from 30% in 2023)  
✅ Cloud computing (AWS/Azure) offers competitive differentiation  
✅ Business Intelligence tools (Tableau/Power BI) critical for mid-level roles  
✅ Entry-level salaries: $60K-$90K; Senior roles: $150K-$250K

---

## 📂 Project Structure
```
├── data/
│   ├── lightcast.parquet         # Raw job postings dataset
│   └── eda.parquet                # Cleaned & processed data
├── figures/                        # Generated visualizations
├── data_cleaning.qmd              # Data preprocessing pipeline
├── eda_d.qmd                      # Exploratory data analysis
├── skill_gap.qmd                  # Skill gap analysis
├── rm_model.qmd                   # Random Forest classification
├── analytics_model.qmd            # K-Means clustering & regression
└── index.qmd                      # Project homepage
```

---

## 📚 Data Source

**Lightcast Job Postings Dataset**  
- 100,000+ real job postings from 2024-2025
- Fields: Title, Company, Location, Salary, Skills, Education, Experience, Industry (NAICS), Occupation (SOC)

---

## 👥 Contributors

**Team 11 - Boston University MET**

Pranjul Garg | Panyang Xiang | Pratham Kabra | Binderiya Dugersuren

---

