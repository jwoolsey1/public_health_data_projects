> Note: This portfolio is a very early work in progress and will be updated regularly with new projects and analyses.

### Initial portfoloio setup ###



# Jaymie Woolsey – Public Health & Healthcare Data Portfolio

Welcome! This portfolio highlights my experience and skills in public health data analysis, program evaluation, and healthcare analytics. I thrive in remote, focused environments, bringing meticulous attention to detail, integrity, and a strong ability to learn new technologies quickly.

---

## About Me

I am a Public Health Analyst II (Data Analyst II) with experience building and managing health data systems from the ground up. I have a background in Clinical Laboratory Science (Microbiology with a Minor in Chemistry) and am skilled in translating complex public health and clinical data into actionable insights.

**Core Strengths:**
- Data extraction, cleaning, and analysis using **R**, **Python**, **SQL**, and **Excel**
- Dashboard and visualization creation with **Tableau**
- Program evaluation, trend analysis, and reporting
- Translating technical results into actionable public health insights
- Strong communication and teamwork in professional and collaborative settings
- Quick learner with a passion for scientific data and analytics

---

## Skills

| Category | Tools & Technologies |
|----------|--------------------|
| Data Analysis | R, Python, SQL, Excel, SAS, SPSS |
| Data Visualization | Tableau, R Shiny, ggplot2 |
| Database Management | Data extraction, cleaning, and reporting from structured & unstructured data |
| Statistics & Modeling | Linear regression, forecasting, trend analysis, risk assessment |
| Public Health | Program evaluation, epidemiology reporting, SUD & STD outreach analysis |
| Collaboration | Team-based projects, stakeholder communication, cross-functional collaboration |

---

## Projects & Experience

### Public Health Data System – Trinity County
- Built the county’s first sustainable health data infrastructure from scratch.
- Extracted and analyzed health, death, and birth record data.
- Developed dashboards and maps to visualize trends and health disparities.
- Evaluated public health programs using data-driven methods to improve outcomes.
- Tracked community outreach for SUD and STD populations and assessed program effectiveness.

### Clinical Laboratory Experience
- Collected, processed, and documented blood, serum, and urine samples.
- Supported Microbiology, Hematology, and Chemistry departments in testing and quality control.
- Applied rigorous scientific methods to ensure accuracy and reliability of lab data.

### Academic Research – California State University, Chico
- Conducted microbiology and chemistry research using LC/MS, GC/MS, immunoassays, ELISA, FT-IR, and GC-FID.
- Analyzed and interpreted complex data, increasing research accuracy and reproducibility.
- Applied statistical modeling and trend analysis to scientific experiments.

---

## Certifications & Education
- **R Programming Certification**
- **Bachelor of Science – Clinical Laboratory Science** (Microbiology focus, Minor in Chemistry)  
  California State University, Chico

---

## Contact Me
- **Email:** [jaymiewoolsey@gmail.com](mailto:jaymiewoolsey@gmail.com)
- **LinkedIn:** [www.linkedin.com/in/jwoolsey1]  
- **GitHub:** [https://github.com/jwoolsey1](https://github.com/jwoolsey1)  











# public_health_data_projects
Data Analysis Projects

# Public Health Data Portfolio

## Overview
This repository is a SAMPLE ONLY and demonstrates generic public health data analysis, visualization, and dashboard creation using synthetic datasets. It showcases skills in R, Python, SQL, Tableau, and Shiny for a Healthcare Data Analyst portfolio.

## Contents
- **data/**: Synthetic datasets simulating health, birth, and death records
- **scripts/**: R and Python scripts for cleaning, analysis, visualization, and modeling
- **notebooks/**: Example R Shiny notebooks for interactive dashboards and how to use SparkR
- **dashboards/**: GGPlot2 and Tableau and descriptions of analytic insights

## Skills Demonstrated
- Data extraction, cleaning, and manipulation
- Exploratory data analysis and trend visualization
- Regression and predictive modeling
- Dashboard development in Tableau and Shiny
- Working with synthetic healthcare datasets while maintaining privacy

## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/jwoolsey1/public-health-data-portfolio.git

# R example packages - This is not real
install.packages(c("tidyverse", "ggplot2", "shiny", "dplyr"))

# Python
pip install pandas matplotlib seaborn jupyter

### **Sample R Script: `data_cleaning.R`**

```r
# Load libraries
library(tidyverse)

# Load synthetic data
birth_data <- read_csv("data/synthetic_birth_data.csv")
death_data <- read_csv("data/synthetic_death_data.csv")
health_data <- read_csv("data/synthetic_health_data.csv")

# Clean and merge datasets
clean_birth <- birth_data %>%
  filter(!is.na(age_mother)) %>%
  mutate(year = as.numeric(year))

clean_death <- death_data %>%
  filter(!is.na(cause_of_death))

merged_data <- clean_birth %>%
  inner_join(clean_death, by = "county")

# Save cleaned dataset
write_csv(merged_data, "data/cleaned_health_data.csv")
Sample Python Script: exploratory_analysis.py
python
Copy code
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load cleaned data
data = pd.read_csv("data/cleaned_health_data.csv")

# Summary statistics
print(data.describe())

# Example plot
plt.figure(figsize=(10,6))
sns.countplot(data=data, x="cause_of_death")
plt.title("Distribution of Causes of Death")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()


### Interactive Dashboarding Samples **

# R_shiny_dashboard_demo.R can showcase ability to make filters, visualizations, and summary tables.

# interactive_dashboard_demo.ipynb can show Python visualizations or Tableau screenshots embedded in Markdown.


### Sample Python Script: exploratory_analysis.py **

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load cleaned data
data = pd.read_csv("data/cleaned_health_data.csv")

# Summary statistics
print(data.describe())

# Example plot
plt.figure(figsize=(10,6))
sns.countplot(data=data, x="cause_of_death")
plt.title("Distribution of Causes of Death")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()



### "Initial portfolio setup" ###
