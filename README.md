# Credit Risk Analysis & Prediction Model

### Minimizing Financial Default using Machine Learning
**Project Focus:** Banking Strategy | Risk Management | Predictive Analytics

![Python](https://img.shields.io/badge/Python-Expert-0077B5?style=flat-square) ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E?style=flat-square) ![Business Strategy](https://img.shields.io/badge/Strategy-Risk_Aversion-0077B5?style=flat-square)

---

### Executive Summary
In the banking sector, the cost of a "False Negative" (approving a bad loan) is significantly higher than a "False Positive" (rejecting a good loan). 

This project analyzes German credit data to build a scoring model that prioritizes **Capital Preservation**. By adjusting the algorithm's sensitivity, I successfully increased the detection of potential defaulters (**Recall**) from **27% to 71%**, significantly reducing the bank's exposure to toxic debt.

---

### Key Business Insights
1.  **The "Danger Zone":** Analysis revealed a high concentration of default risk in applicants **under 30 years old** requesting credits above 5,000 DM.
2.  **Risk Calibration:** The initial model had high accuracy (72%) but failed to detect risk. The optimized model sacrifices marginal accuracy (68%) to achieve a **2.5x improvement in risk detection**.

### Technical Implementation
* **Data Cleaning:** Handled missing financial records and mapped German legacy terms to Business English standard variables.
* **Visualization:** Created scatter plots (Age vs. Amount) to identify risk clusters visually.
* **Machine Learning:**
    * Algorithm: `Logistic Regression` (Chosen for interpretability in a regulated sector).
    * Optimization: Applied `StandardScaler` and `Class Weight Balancing` to correct bias towards the majority class.

### Model Performance (Confusion Matrix)
| Metric | Value | Business Impact |
| :--- | :--- | :--- |
| **Accuracy** | 68% | Overall correctness of the system. |
| **Recall (Bad Credit)** | **71%** | **Critical Metric:** Percentage of actual defaulters correctly identified and rejected. |
| **Precision** | 49% | Accepted trade-off to ensure maximum safety. |

---

### How to Run This Project
1.  Clone the repository.
2.  Install dependencies: `pandas`, `seaborn`, `scikit-learn`.
3.  Run `Credit_Risk_Scoring_Model.ipynb` to see the training process and visualizations.

---
*"Banking is not about avoiding risks, but about managing them intelligently."*
