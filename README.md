# International Student Mental Health Analysis
### Descriptive Dashboards and Predictive Modeling Visuals

This repository provides the complete visual outputs supporting the research project:

**“A Multi-faceted Analysis of International Student Mental Health: From Descriptive Insights to Predictive Modeling.”**

It serves as a supplementary extension for judges and reviewers to explore all dashboards, model outputs, and analytical visuals in high resolution.

---

## Project Overview

International students experience cultural, academic, and social stressors that increase vulnerability to anxiety and depression.

This project integrates:

- Descriptive analytics using SAS Viya for Learners
- Machine learning predictive modeling (Random Forest + SMOTE)  implemented in a Jupyter extension on SAS Viya Workbench with Python
- High-resolution dashboards and evaluation visuals

The objective is to support early identification of students at risk and inform targeted mental health interventions.

---

## Repository Contents

### Descriptive Dashboards

Visual analyses illustrating:

- Demographic distribution
- Anxiety patterns across psychosocial factors
- Depression determinants
- Overwhelm and university service utilization
- Role of belonging and perceived support

These dashboards highlight consistent associations between lower social support, cultural adjustment difficulties, and increased psychological distress.

---

### Predictive Model Results

The final Random Forest model integrated with SMOTE achieved:

- **Accuracy:** 83.33%
- **AUC-ROC:** 0.8555
- **Precision (Depression):** 0.81
- **Recall (Depression):** 0.74

Included evaluation visuals:

- Confusion Matrix
- ROC Curve
- Performance Summary

These results demonstrate strong discriminatory ability in identifying at-risk students.

## 📁 Repository Structure

```
├── Dashboards/
│   ├── Anexity_Dashboard.png
│   ├── Depression_dashboard.png
│   ├── overwhelmed_dashboard.png
│   ├── mental_health_variables.png
│   ├── repondents_dashboard.png
│
├── figures/
│   ├── confusion_matrix.png
│   ├── ROC_curve.png
│
└── README.md
```

## Analytical Workflow Summary

1. Data cleaning and preprocessing  
2. Feature selection guided by prior research  
3. Label encoding and binary target mapping  
4. 70/30 train-test split  
5. SMOTE-based class balancing  
6. Random Forest classification  
7. Performance evaluation using Accuracy and AUC-ROC  

---

## ⚠ Study Limitations

- Predictive dataset size (N = 197) may limit generalizability.
- Cross-sectional descriptive design prevents causal inference.
- Future validation using larger and longitudinal datasets is recommended.

---

## Purpose of This Repository

This repository ensures transparency and allows reviewers to:

- Examine high-resolution visuals
- Validate model performance
- Review analytical outputs clearly
- Access organized supplementary materials

