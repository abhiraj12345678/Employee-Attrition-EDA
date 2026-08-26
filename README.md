## Categorical Proportion Analysis

The categorical proportion analysis was performed to understand the distribution of different categories within the dataset.

### Key Observations

* **Gender:** Relatively balanced, with Male employees representing **54.93%** and Female employees **45.07%**.
* **Job Level:** Fairly balanced across Entry-level (**40.05%**), Mid-level (**39.86%**), and Senior (**20.10%**) employees.
* **Job Role:** Technology is the largest category (**26.02%**), while Finance is the smallest (**14.07%**).
* **Work-Life Balance:** Good represents **37.80%**, while Poor represents **13.94%**.
* **Job Satisfaction:** High satisfaction dominates at **49.97%**, while Low represents only **9.88%**.
* **Performance Rating:** Average is strongly dominant at **60.09%**.
* **Overtime:** **67.36%** of employees report No overtime, while **32.64%** report Yes.
* **Education Level:** Bachelor's degree holders represent **29.91%**, while PhD holders represent only **5.18%**.
* **Marital Status:** Married (**50.18%**), Single (**34.96%**), and Divorced (**14.86%**).
* **Leadership Opportunities:** Highly imbalanced, with **95.10%** reporting No opportunities and only **4.90%** reporting Yes.
* **Remote Work:** **80.94%** report No remote work, while **19.06%** report Yes.
* **Innovation Opportunities:** **83.72%** report No opportunities, compared with **16.28%** reporting Yes.
* **Company Size:** Medium (**49.91%**), Small (**30.09%**), and Large (**20.00%**).
* **Company Reputation:** Good (**49.94%**), Poor (**20.19%**), Fair (**19.83%**), and Excellent (**10.04%**).
* **Employee Recognition:** Low (**39.86%**), Medium (**30.26%**), High (**24.91%**), and Very High (**4.97%**).

### Important Findings

The dataset contains both relatively balanced and highly imbalanced categorical variables.

The strongest imbalance is observed in:

1. **Leadership Opportunities:** 95.10% No
2. **Innovation Opportunities:** 83.72% No
3. **Remote Work:** 80.94% No
4. **Performance Rating:** 60.09% Average

Smaller categories such as **PhD (5.18%)** and **Very High Employee Recognition (4.97%)** should be interpreted carefully because they contain fewer observations.

### Machine Learning Relevance

These distributions are important before building the employee attrition prediction model. Highly imbalanced categorical features may affect model learning and interpretation. Therefore, both **category proportions and actual sample sizes** should be considered when analyzing their relationship with employee attrition.

This analysis also helps identify potential features that may provide useful information for further **EDA, feature engineering, and machine learning model development**.
