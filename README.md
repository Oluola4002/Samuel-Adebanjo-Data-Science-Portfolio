# 🎓 Samuel Adebanjo — Data Science Portfolio
### *AltSchool Africa Data Science Portfolio: Exploratory Data Analysis, Machine Learning, Statistical Modeling & Applied Visual Analytics*

[![Python](https://img.shields.io/badge/Python-3.9%20%7C%203.10%20%7C%203.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c72b0?style=for-the-badge)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📌 Portfolio Overview

Welcome to the **Data Science Portfolio** of **Samuel Oluolamide Adebanjo**. This repository houses applied data science projects, statistical modeling, and deep exploratory analyses developed as part of the AltSchool Africa Data Science program and personal research.

### Featured Project:
**🎓 U.S. Education System: Equity, Finance & Academic Performance Analytics**  
An in-depth empirical investigation into **5,000 U.S. educational institutions**, analyzing how socioeconomic factors, per-pupil expenditures, and STEM certifications correlate with academic achievement and student equity.

---

## 📂 Repository Structure

```plaintext
Samuel-Adebanjo-Data-Science-Portfolio/
│
├── Portfolio/
│   ├── Data/
│   │   └── us_education_system_dataset.csv     # 5,000 U.S. educational institutions dataset (35 features)
│   │
│   └── Notebook/
│       └── Data_visualization.ipynb            # Publication-ready U.S. Education EDA & visual analytics
│
├── .gitignore                                  # Git exclusion configuration for data science
├── LICENSE                                     # MIT Open Source License
├── README.md                                   # Comprehensive portfolio showcase documentation
└── requirements.txt                            # Python environment dependencies
```

---

## 🔬 Featured Study: U.S. Education System Analytics

### Key Research Questions
1. **Socioeconomic Impact on Performance:**  
   *To what extent does socioeconomic disadvantage (proxied by Free/Reduced Price Lunch eligibility and Title I status) correlate with proficiency gaps in Mathematics and Reading?*
2. **Resource Allocation & ROI:**  
   *Does increased per-pupil expenditure ($ USD) yield measurable improvements in high school graduation rates and reductions in chronic absenteeism?*
3. **Institutional Governance & Funding Dynamics:**  
   *How do revenue structures (Federal, State, Local) diverge across Public, Charter, and Private institutions?*
4. **STEM Intervention & College Readiness:**  
   *Does formal STEM accreditation correlate with higher standardized test performance (SAT/ACT) and postsecondary matriculation rates?*
5. **The Digital Divide:**  
   *What is the statistical relationship between community household broadband access and student academic proficiency?*

---

## 📊 Core Analytical Findings

| Dimension | Primary Metric / Indicator | Key Finding & Statistical Takeaway |
| :--- | :--- | :--- |
| **Socioeconomic Disparities** | Free/Reduced Lunch vs. Proficiency | **Strong negative correlation** with both Math and Reading proficiency scores, confirming that poverty remains the primary systemic predictor of standardized testing performance. |
| **Federal Assistance** | Title I Program Categorization | Schools with Title I Schoolwide status serve significantly higher concentrations of under-resourced students, demonstrating the targeted reach of federal funding initiatives. |
| **STEM Accreditation** | STEM Certified Flag | High schools holding STEM certification exhibit higher mean SAT/ACT scores and higher postsecondary enrollment rates relative to non-certified institutions. |
| **Absenteeism & Completion** | Chronic Absenteeism vs. Graduation | Chronic absenteeism strongly correlates with depressed graduation rates and elevated student-to-teacher ratios, underscoring attendance as a critical leading indicator. |
| **Digital Equity** | Community Broadband Access | Household broadband access demonstrates a consistent positive relationship with academic performance, highlighting connectivity as foundational public educational infrastructure. |

---

## 📋 Data Dictionary (`us_education_system_dataset.csv`)

| Category | Columns | Description |
| :--- | :--- | :--- |
| **Identification & Geography** | `institution_id`, `institution_name`, `state_code`, `state_name`, `county`, `nces_locale` | Unique identifiers, geographic location, and NCES urbanicity classifications (City, Suburb, Town, Rural). |
| **Governance & Classification** | `level`, `control`, `title_i_status` | School tier (Elementary, Middle, High School, University), governing model (Public, Charter, Private), and Title I status. |
| **Capacity & Demographics** | `total_enrollment`, `number_of_teachers`, `student_teacher_ratio`, `racial_*_pct` | Enrollment size, instructional faculty headcount, student-teacher ratio, and racial demographic breakdown. |
| **Special Populations** | `special_education_pct`, `english_learner_pct`, `percent_free_reduced_lunch` | Percentages of students receiving special education services, English language learners, and free/reduced lunch recipients. |
| **Institutional Finance** | `per_pupil_expenditure_usd`, `federal_funding_pct`, `state_funding_pct`, `local_funding_pct` | Annual expenditure per pupil in USD and revenue distribution across federal, state, and local sources. |
| **Academic Outcomes** | `math_proficiency_pct`, `reading_proficiency_pct`, `graduation_rate_pct`, `chronic_absenteeism_pct` | Academic assessment pass rates, on-time graduation percentage, and chronic absenteeism rate. |
| **Secondary & College Prep** | `avg_sat_score`, `avg_act_score`, `ap_ib_participation_pct`, `postsecondary_enrollment_pct` | High school college readiness benchmarks (SAT, ACT, AP/IB participation, college matriculation). |
| **Technology & Programs** | `stem_certified_flag`, `broadband_access_pct` | STEM curriculum certification flag and estimated community broadband connectivity rate. |

---

## 🚀 Quickstart & Reproduction Guide

### 1. Clone the Repository
```bash
git clone https://github.com/Oluola4002/Samuel-Adebanjo-Data-Science-Portfolio.git
cd Samuel-Adebanjo-Data-Science-Portfolio
```

### 2. Set Up Virtual Environment (Recommended)
```bash
# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
.\venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch the Analysis
```bash
jupyter notebook Portfolio/Notebook/Data_visualization.ipynb
```
*Note: The notebooks feature dynamic relative path resolution and execute seamlessly in JupyterLab, VS Code, and Google Colab.*

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3.9+
- **Data Manipulation & Analysis:** `pandas`, `numpy`
- **Statistical Modeling:** `scipy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Notebook Environment:** `jupyter`, `ipykernel`

---

## 👨‍💻 About the Author

**Samuel Oluolamide Adebanjo**  
*Aerospace Engineer (First Class Honours, 4.97 CGPA) | AltSchool Africa Data Science Fellow*

- **GitHub:** [@Oluola4002](https://github.com/Oluola4002)
- **Repository:** [Samuel-Adebanjo-Data-Science-Portfolio](https://github.com/Oluola4002/Samuel-Adebanjo-Data-Science-Portfolio)
- **Email:** [samueloluola.a@gmail.com](mailto:samueloluola.a@gmail.com)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for complete details.
