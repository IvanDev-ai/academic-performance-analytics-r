# Academic Performance Analytics: Statistical Modeling and Data Insights in R

### Applied Data Analytics Project — PHE Applied Computing & Artificial Intelligence

**Author:** Iván Lumbreras Martín  
**Academic Year:** 2024–2025  

---

## 1. Overview

This project delivers a **rigorous statistical analysis of academic performance**, leveraging **R** to convert raw educational data into **high-value analytical insights**.

Rather than focusing solely on descriptive visualization, the project emphasizes:

* **Statistical rigor and hypothesis validation**
* **Distribution modeling and assumption testing**
* **Identification of key drivers behind academic success**

The entire workflow is designed as a **fully reproducible analytical pipeline**, integrating data ingestion, transformation, modeling, and reporting within a unified environment.

---

## 2. Analytical Approach & Methodology

The project follows industry-grade data science practices:

### Exploratory Data Analysis (EDA)
A structured approach to uncover patterns, anomalies, and variable relationships prior to modeling.

### Inferential Statistics
Application of hypothesis testing to evaluate whether observed differences are statistically significant, assuming normality:

$$
f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2}
$$

### Reproducible Research
Implementation in **R Markdown**, ensuring that the entire analytical process is:

* Transparent  
* Auditable  
* Fully reproducible  

---

## 3. Core Analytical Capabilities

* **Multivariate Correlation Analysis**  
  Detection of hidden relationships between socioeconomic variables and academic outcomes.

* **Statistical Distribution Profiling**  
  Validation of normality using histograms and Q-Q plots.

* **Data Wrangling Pipeline**  
  Advanced use of the **tidyverse** ecosystem for clean, efficient, and non-destructive data transformation.

* **High-Fidelity Data Visualization**  
  Precision-oriented visual outputs using **ggplot2**, tailored for analytical clarity and academic reporting.

---

## 4. Data Quality & Statistical Validity

Robust controls are implemented to ensure analytical integrity:

* **Outlier Detection**  
  Combination of **Tukey’s fences** and **Z-score analysis**:

$$
z = \frac{x - \mu}{\sigma}
$$

* **Assumption Verification**  
  Validation of:
  * Normality  
  * Homoscedasticity  
  prior to applying parametric tests

* **Modular Code Structure**  
  Separation of concerns across:
  * Data loading  
  * Transformation  
  * Analysis  
  * Visualization  

---

## 5. Technology Stack

| Category | Tools / Concepts |
|---|---|
| Language | R |
| Libraries | tidyverse (`dplyr`, `ggplot2`, `tidyr`), `rmarkdown`, `knitr` |
| Reporting | Pandoc, LaTeX |
| Concepts | EDA, Statistical Inference, Regression, Data Cleaning |

---

## 6. Impact & Key Takeaways

This project demonstrates the ability to:

* Translate raw datasets into **statistically validated insights**
* Apply **rigorous analytical methodologies** beyond surface-level analysis
* Build **reproducible data workflows** aligned with professional standards
* Ensure **data integrity and scientific reliability** in decision-making contexts

---

## 7. Future Enhancements

* **Predictive Modeling**
  * Integration of **Random Forest** models to identify at-risk students

* **Interactive Analytics**
  * Migration to a **Shiny dashboard** for real-time data exploration

* **Bayesian Methods**
  * Extension toward probabilistic modeling for improved forecasting

---

## 8. Repository Structure

* `/data` — Raw and processed datasets (anonymized)  
* `/notebooks` — R Markdown files containing analytical workflows  
* `/output` — Generated reports (PDF / HTML)  

---

## 9. Academic Context

Developed as part of the **Applied Computing & Artificial Intelligence program**, this project reflects the transition from academic exercises to **professional-grade data analysis workflows**.

---

## Author

**Iván Lumbreras Martín**  
Computer Science Graduate | Junior Data Scientist / Software Engineer  

**Specialized in:** Statistical Computing, Data Integrity & Analytical Modeling  

---

*Last updated: May 2026*
