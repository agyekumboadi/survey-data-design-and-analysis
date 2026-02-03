# Data Design – Customer Behaviour Analysis (Tesco Case Study)

This repository contains my Data Design case study, where I designed, prepared and analysed real customer survey data to support business decision-making.

The objective was to determine whether staff interaction influences customer purchasing behaviour at Tesco using statistical and data-driven methods.

---

## Business Problem

Tesco wanted to understand:

> “Do customers still make purchases if they do not meet a specific staff member on duty?”

This helps Tesco evaluate:
- Whether staff turnover affects sales
- Whether customer loyalty is linked to individuals or the brand
- How automated and staff-based services compare

---

## Dataset

The dataset was collected using a structured customer survey.  
It includes:

- Customer shopping frequency  
- Perception of Tesco staff  
- Whether purchases depend on staff recommendations  
- Customer satisfaction ratings (1–5 scale)  
- Whether customers would purchase without meeting a specific staff member  

---

## Key Variables

**Dependent variable**
- `Will_You_Purchase_If_You_Do_Not_Meet_that_Staff_On_Duty`

**Independent variables**
- Shopping frequency  
- Staff-customer relationship rating  
- Staff recommendations  
- Customer satisfaction score  

These variables were created and validated in Python and Jamovi.

---

## Data Preparation

The dataset was cleaned and prepared using Python (pandas) and Jamovi:

- Duplicate checks  
- Missing values handling  
- Removal of unused variables  
- Outlier detection and removal  
- Data type validation  
- Statistical summaries (mean, median, standard deviation)

This ensured high data quality before statistical testing.

---

## Tools Used

| Tool | Purpose |
|------|--------|
| Python (pandas, matplotlib, seaborn) | Data cleaning, visualisation, variable creation |
| Jamovi | Descriptive statistics, outlier detection, hypothesis testing |
| Excel | Initial data inspection |
| Jupyter Notebook | Code execution and analysis |

---

## Statistical Analysis

Because the data was ordinal and non-normal, a **Kruskal-Wallis (One-Way ANOVA non-parametric test)** was selected.

This tested whether customer satisfaction differed depending on staff interaction.

**Result**

p-value = **0.093**  

Since p > 0.05, the result shows:

> There is **no statistically significant relationship** between staff interaction and whether customers make purchases.

Customers will purchase even if they do not meet a specific staff member.

---

## Business Insight

This means Tesco’s brand and service consistency is stronger than individual staff dependency.

Tesco can:
- Use automation and self-service safely
- Manage staff rotation without harming sales
- Focus on service quality rather than specific employees

---

## Project Structure

**msc-data-design/**
- **data/** – Survey dataset (CSV / Excel) or data description  
- **notebooks/** – Python / analysis notebooks (if applicable)  
- **reports/** – Arden Data Design essay and report (PDF)  
- **outputs/** – Charts, statistical results, Jamovi/Python outputs  
- **assets/** – Screenshots of surveys and figures used in report  
- **README.md** – Project documentation


---

## Author

Samuel Boadi Agyekum  
MSc Data Analytics & IT Security Management (Distinction)  
Arden University  
GitHub: https://github.com/agyekumboadi

