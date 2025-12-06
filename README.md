# Medical-Risk-Stratification-Using-Machine-Learning

## Objective
This project focuses on developing machine learning models capable of classifying individuals into medical risk categories using demographic, lifestyle, clinical, and healthcare-utilization features. The dataset includes a pre-computed **`risk_score`**, from which two target variables were engineered:

---

## 1. Three-Class Risk Indicator
- **Low**
- **Medium**
- **High**

## 2. Binary Risk Indicator
- **Low**
- **High**

---

Both target formulations are evaluated to determine which approach provides greater practical value in real-world clinical and insurance decision-making.

The **three-class model** enables a more detailed understanding of patient profiles and their progression along a risk spectrum. In contrast, the **binary model** offers a simplified high-priority signal that may be more actionable for general practitioners who must quickly identify patients requiring additional assessment.

By comparing predictive performance, interpretability, and clinical relevance, this project aims to identify which risk-stratification strategy is most suitable as a decision-support tool for **primary care workflows** and **insurance screening processes**.
