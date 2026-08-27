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

* **Remote Work:** **80.94%** report No remote work, while **19.06%** report Yes.

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

---

## Attrition-Focused Findings

The categorical analysis was further extended by calculating the attrition rate within each category.

Several important patterns were identified:

* **Job Level:** Entry-level employees have the highest attrition rate at **63.19%**, compared with **45.56%** for Mid-level and **20.31%** for Senior-level employees.

* **Marital Status:** Single employees have the highest attrition rate at **66.83%**, compared with **40.70%** for Divorced and **36.15%** for Married employees.

* **Work-Life Balance:** Employees with Poor work-life balance have the highest attrition rate at **60.11%**, compared with **35.81%** for Excellent work-life balance.

* **Company Reputation:** Employees in companies with a Poor reputation have the highest attrition rate at **56.50%**.

* **Age Group:** Employees aged **18–25** have the highest attrition rate at **53.19%**.

* **Years at Company:** Employees with **0–5 years** at the company have the highest attrition rate at **53.20%**, followed by **6–10 years at 51.57%**. Attrition generally decreases with longer time at the company, reaching **43.91%** for employees with 21+ years.

* **Company Tenure:** Attrition is highest among employees in the **0–25** tenure group at **50.58%** and generally decreases with longer tenure, reaching **44.21%** for the **101+** group.

* **Remote Work:** Non-remote employees have an attrition rate of **52.89%**, compared with **24.86%** among remote employees.

* **Overtime:** Employees who work overtime have an attrition rate of **51.54%**, compared with **45.61%** for employees who do not.

* **Income Group:** The Low income group has the highest attrition rate at **50.72%**.

* **Education Level:** Bachelor's degree holders have the highest attrition rate at **49.32%**, while the PhD group has the lowest at **24.86%**.

* **Company Size:** Small companies have the highest attrition rate at **49.87%**, although the difference between company-size categories is relatively small.

* **Leadership Opportunities:** Employees without leadership opportunities have an attrition rate of **47.66%**, compared with **45.31%** among employees with opportunities.

* **Innovation Opportunities:** Employees without innovation opportunities have an attrition rate of **48.02%**, compared with **45.11%** among employees with opportunities.

* **Employee Recognition:** Attrition rates are very similar across recognition levels, ranging from **46.14% to 47.83%**, suggesting a relatively weak association.

---

## Monthly Income and Attrition

Monthly Income was compared between employees who left and employees who stayed.

* **Employees who left:** Mean Monthly Income = **7,726.69**
* **Employees who stayed:** Mean Monthly Income = **7,325.70**
* **t-statistic:** **-2.78**
* **p-value:** **0.0055**

Since the p-value is below **0.05**, the analysis indicates a **statistically significant difference in Monthly Income between employees who left and employees who stayed**.

---

## Strongest Categorical Associations

The difference between the highest and lowest attrition rates within each categorical feature was compared.

1. **Job Level:** **42.88 percentage points**
2. **Marital Status:** **30.68 percentage points**
3. **Remote Work:** **28.03 percentage points**
4. **Education Level:** **24.46 percentage points**
5. **Work-Life Balance:** **24.30 percentage points**

Therefore, **Job Level shows the strongest variation in attrition rate among the categorical variables analyzed**.

---

# Numerical Relationship Analysis

Correlation analysis was performed to examine linear relationships between numerical variables.

### 1. Age vs Monthly Income

The correlation between Age and Monthly Income is **-0.00**, indicating almost no linear relationship between the two variables.

The scatter plot also shows that Monthly Income is widely distributed across different age groups.

**Conclusion:** Age does not appear to be strongly associated with Monthly Income in this dataset.

### 2. Age vs Years at Company

The correlation between Age and Years at Company is **0.54**, indicating a **moderate positive relationship**.

The scatter plot shows an upward pattern, suggesting that older employees generally tend to have more years at the company.

**Conclusion:** Age and Years at Company have a noticeable positive relationship.

### 3. Years at Company vs Monthly Income

The correlation between Years at Company and Monthly Income is **-0.01**, indicating almost no linear relationship.

**Conclusion:** Years at Company does not appear to be strongly associated with Monthly Income.

### 4. Number of Promotions vs Years at Company

The correlation between Number of Promotions and Years at Company is **-0.00**, indicating almost no linear relationship.

**Conclusion:** The number of promotions does not appear to be strongly associated with Years at Company in this dataset.

### 5. Distance from Home vs Attrition

Distance from Home was divided into groups to compare attrition rates:

- **0–5:** 42.19%
- **6–10:** 41.70%
- **11–20:** 41.53%
- **21–30:** 42.74%
- **31+:** 49.91%

The **31+ distance group has the highest attrition rate at 49.91%**, while the **11–20 group has the lowest at 41.53%**.

**Conclusion:** Employees living farther from the workplace, particularly those in the 31+ group, show somewhat higher attrition. However, the differences across most groups are relatively small.

### 6. Training Hours vs Attrition

The dataset does not contain a **Training Hours** column. Therefore, the relationship between Training Hours and Attrition could not be analyzed.

---

## 7. Correlation Matrix / Heatmap

A correlation heatmap was created to examine linear relationships among the numerical variables.

The strongest relationships observed were:

- **Age ↔ Years at Company:** **0.54**
- **Years at Company ↔ Company Tenure:** **0.44**
- **Age ↔ Company Tenure:** **0.24**

Most other numerical variables showed very weak linear correlations.

**Conclusion:** Age, Years at Company, and Company Tenure show the most noticeable numerical relationships, while Monthly Income, Number of Promotions, Distance from Home, and Number of Dependents have relatively weak linear relationships with the other numerical variables.

Employee ID was not interpreted because it is an identifier rather than a meaningful analytical variable.

---

# Categorical Relationship Analysis

Normalized cross-tabulations and heatmaps were used to examine relationships between selected categorical variables.

### 8. Job Satisfaction vs Work-Life Balance

The distributions of Work-Life Balance were highly similar across Job Satisfaction levels.

For example, Good Work-Life Balance ranged from **37.07% to 38.11%** across satisfaction categories.

**Conclusion:** Job Satisfaction and Work-Life Balance do not show a strong categorical relationship in this dataset.

### 9. Job Satisfaction vs Performance Rating

Performance Rating was distributed very similarly across Job Satisfaction levels.

Average Performance Rating ranged from **59.88% to 60.67%**, while High Performance Rating ranged from **19.70% to 20.11%**.

**Conclusion:** Job Satisfaction and Performance Rating do not show a strong categorical relationship.

### 10. Employee Recognition vs Job Satisfaction

Job Satisfaction distributions were highly similar across Employee Recognition levels.

High Job Satisfaction ranged from **48.80% to 50.32%**, while Low Job Satisfaction ranged from **9.58% to 10.08%**.

**Conclusion:** Employee Recognition and Job Satisfaction do not show a strong categorical relationship.

### 11. Remote Work vs Work-Life Balance

Work-Life Balance distributions were almost identical between remote and non-remote employees.

For example:

- Good WLB: **37.88%** for non-remote vs **37.44%** for remote
- Poor WLB: **13.92%** for non-remote vs **14.01%** for remote

**Conclusion:** Remote Work and Work-Life Balance do not show a strong categorical relationship.

### 12. Overtime vs Work-Life Balance

A normalized cross-tabulation and heatmap were created to examine the relationship between Overtime and Work-Life Balance.

**Conclusion:** The final interpretation should be added after reviewing the generated output.

### 13. Leadership Opportunities vs Job Level

The distribution of Job Level was very similar among employees with and without leadership opportunities.

- Entry: **40.01%** without vs **40.85%** with opportunities
- Mid: **39.89%** without vs **39.10%** with opportunities
- Senior: **20.10%** without vs **20.05%** with opportunities

**Conclusion:** Leadership Opportunities and Job Level do not show a strong categorical relationship.

### 14. Innovation Opportunities vs Job Role

The distribution of Job Roles was highly similar among employees with and without innovation opportunities.

Technology represented:

- **26.00%** among employees without innovation opportunities
- **26.14%** among employees with innovation opportunities

Finance represented:

- **14.07%** among employees without innovation opportunities
- **14.08%** among employees with innovation opportunities

**Conclusion:** Innovation Opportunities and Job Role do not show a strong categorical relationship.

---

# Combination Analysis

A combination analysis was performed to identify employee groups with particularly high attrition.

The highest observed attrition rate was found among:

> **Entry-level employees + Overtime = Yes + Poor Work-Life Balance → 80.16% attrition**

Other high-attrition combinations included:

- **Entry + Overtime Yes + Fair Work-Life Balance → 76.34%**
- **Entry + Overtime No + Poor Work-Life Balance → 73.32%**
- **Entry + Overtime No + Fair Work-Life Balance → 70.95%**
- **Mid + Overtime Yes + Poor Work-Life Balance → 65.17%**

These results suggest that multiple employee and workplace factors may interact and collectively be associated with employee attrition.

Because combination-based groups may contain fewer observations than the overall dataset, these high attrition rates should be interpreted alongside their corresponding sample sizes.

---

# Overall EDA Insights

The analysis indicates that employee attrition is associated with several employee, job, and workplace characteristics.

The strongest patterns were observed for:

- **Job Level**
- **Marital Status**
- **Work-Life Balance**
- **Remote Work**
- **Company Reputation**
- **Age Group**
- **Years at Company**
- **Overtime**

Among the categorical variables analyzed, **Job Level showed the largest difference in attrition rates**, with a **42.88 percentage-point gap** between Entry-level and Senior-level employees.

The combination analysis further identified **Entry-level employees working overtime with Poor Work-Life Balance** as the group with the highest observed attrition rate (**80.16%**).

The numerical relationship analysis showed a moderate positive relationship between **Age and Years at Company (0.54)**, while most other numerical variable pairs showed weak or negligible linear relationships.

Overall, these findings provide useful directions for **feature engineering, statistical testing, and employee attrition prediction modeling**. However, the observed relationships represent **associations rather than causal relationships**.
