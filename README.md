## Categorical Proportion Analysis

The categorical proportion analysis was performed to understand the distribution of different categories within the dataset and to identify potential imbalances before analyzing their relationship with employee attrition.

### Key Observations

* **Gender:** Relatively balanced, with Male employees representing **54.93%** and Female employees **45.07%**.

* **Job Level:** Entry-level employees represent **40.05%**, Mid-level employees **39.86%**, and Senior-level employees **20.10%**.

* **Job Role:** Technology is the largest category (**26.02%**), while Finance is the smallest (**14.07%**).

* **Work-Life Balance:** Good represents the largest category (**37.80%**), while Poor represents **13.94%**.

* **Job Satisfaction:** High satisfaction is the dominant category (**49.97%**), while Low satisfaction represents **9.88%**.

* **Performance Rating:** Average performance is strongly dominant at **60.09%**.

* **Overtime:** **67.36%** of employees report No overtime, while **32.64%** report Yes.

* **Education Level:** Bachelor's degree holders represent **29.91%**, while PhD holders represent only **5.18%**.

* **Marital Status:** Married employees represent **50.18%**, followed by Single (**34.96%**) and Divorced (**14.86%**).

* **Leadership Opportunities:** Highly imbalanced, with **95.10%** of employees reporting No leadership opportunities and only **4.90%** reporting Yes.

* **Remote Work:** **80.94%** of employees report No remote work, while **19.06%** report Yes.

* **Innovation Opportunities:** **83.72%** report No innovation opportunities, compared with **16.28%** reporting Yes.

* **Company Size:** Medium-sized companies represent **49.91%**, Small companies **30.09%**, and Large companies **20.00%**.

* **Company Reputation:** Good represents **49.94%**, Poor **20.19%**, Fair **19.83%**, and Excellent **10.04%**.

* **Employee Recognition:** Low recognition represents **39.86%**, Medium **30.26%**, High **24.91%**, and Very High only **4.97%**.

### Important Findings

The dataset contains both relatively balanced and highly imbalanced categorical variables.

The strongest category imbalances are observed in:

1. **Leadership Opportunities:** **95.10% No** and **4.90% Yes**
2. **Innovation Opportunities:** **83.72% No** and **16.28% Yes**
3. **Remote Work:** **80.94% No** and **19.06% Yes**
4. **Performance Rating:** **60.09% Average**

Other relatively smaller categories include:

- **PhD:** **5.18%**
- **Very High Employee Recognition:** **4.97%**
- **Senior Job Level:** **20.10%**
- **Excellent Company Reputation:** **10.04%**

These smaller categories should be interpreted carefully because their attrition rates may be influenced by their smaller sample sizes.

### Attrition-Focused Findings

The categorical analysis was further extended by calculating the attrition rate within each category.

Several important patterns were identified:

* **Job Level:** Entry-level employees have the highest attrition rate at **63.19%**, compared with **45.56%** for Mid-level and **20.31%** for Senior-level employees.

* **Work-Life Balance:** Employees with Poor work-life balance have the highest attrition rate at **60.11%**, compared with **35.81%** for Excellent work-life balance.

* **Company Reputation:** Employees in companies with a Poor reputation have the highest attrition rate at **56.50%**.

* **Age Group:** Employees aged **18–25** have the highest attrition rate at **53.19%**.

* **Remote Work:** Non-remote employees have an attrition rate of **52.89%**, compared with **24.86%** among remote employees.

* **Overtime:** Employees who work overtime have an attrition rate of **51.54%**, compared with **45.61%** for employees who do not.

* **Income Group:** The Low income group has the highest attrition rate at **50.72%**.

* **Marital Status:** Single employees have the highest attrition rate at **66.83%**, compared with **40.70%** for Divorced and **36.15%** for Married employees.

* **Education Level:** Bachelor's degree holders have the highest attrition rate at **49.32%**, while the PhD group has the lowest at **24.86%**.

* **Company Size:** Small companies have the highest attrition rate at **49.87%**, although the difference between company-size categories is relatively small.

* **Leadership Opportunities:** Employees without leadership opportunities have an attrition rate of **47.66%**, compared with **45.31%** among employees with opportunities.

* **Innovation Opportunities:** Employees without innovation opportunities have an attrition rate of **48.02%**, compared with **45.11%** among employees with opportunities.

* **Employee Recognition:** Attrition rates are very similar across recognition levels, ranging from **46.14% to 47.83%**, suggesting a relatively weak association.

### Strongest Categorical Associations

When comparing the difference between the highest and lowest attrition rates within each categorical feature, **Job Level** showed the largest difference:

1. **Job Level:** **42.88 percentage points**
2. **Marital Status:** **30.68 percentage points**
3. **Remote Work:** **28.03 percentage points**
4. **Education Level:** **24.46 percentage points**
5. **Work-Life Balance:** **24.30 percentage points**

This indicates that **Job Level shows the strongest variation in attrition rate among the categorical variables analyzed**.

### Combination Analysis

A combination analysis was also performed to identify groups with particularly high attrition.

The highest observed attrition rate was found among:

> **Entry-level employees + Overtime = Yes + Poor Work-Life Balance → 80.16% attrition**

Other combinations also showed high attrition rates, including:

- Entry + Overtime Yes + Fair Work-Life Balance → **76.34%**
- Entry + Overtime No + Poor Work-Life Balance → **73.32%**
- Entry + Overtime No + Fair Work-Life Balance → **70.95%**
- Mid + Overtime Yes + Poor Work-Life Balance → **65.17%**

These results suggest that **multiple employee and workplace factors may interact with each other and collectively be associated with employee attrition**.

### Machine Learning Relevance

Understanding categorical distributions and attrition rates is important before building an employee attrition prediction model.

Highly imbalanced categories should be interpreted carefully because a small category can produce unstable or misleading attrition rates. Therefore, both **attrition percentage and sample size** should be considered together.

The analysis also identified potentially important features such as **Job Level, Marital Status, Remote Work, Work-Life Balance, Age Group, Overtime, and Company Reputation** for further feature engineering and machine learning analysis.

However, these EDA findings represent **associations rather than causal relationships**. Statistical testing and machine learning model evaluation should be used to determine whether these features provide significant predictive value for employee attrition.
