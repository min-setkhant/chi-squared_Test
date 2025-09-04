# chi-squared_Test
The Chi-squared test (χ² test) is a statistical method mainly used when we want to see if there’s a relationship between two categorical variables or if the observed data matches our expected data.


## Why We Use the Chi-Squared Test (χ² Test)

The **Chi-squared test** is a statistical method used when dealing with **categorical data**. It helps answer two main questions:

---

### 1. Association Between Two Categorical Variables

* Example: In the `stent30` dataset, we might want to see if the **30-day outcome (Success/Failure)** depends on whether a **stent was used (Yes/No)**.
* The test checks whether the difference in outcomes is **due to chance** or whether there is a **real relationship** between the variables.

---

### 2. Goodness-of-Fit Test

* Sometimes we have **expected proportions** (e.g., 50% Male, 50% Female), but the observed data might be different (e.g., 40% Male, 60% Female).
* The Chi-squared test tells us whether the observed difference is **statistically significant** or just **random variation**.

---

### 3. Independence Testing Using Contingency Tables

A contingency table shows the counts for combinations of two variables. Example:

|          | Success | Failure | Total |
| -------- | ------- | ------- | ----- |
| Stent    | 40      | 10      | 50    |
| No Stent | 30      | 20      | 50    |

The Chi-squared test checks whether the two variables (Stent and Outcome) are **independent** or **related**.

---

### 4. Why Not Just Look at Percentages?

* Percentages might look different, but the difference could be due to **random chance**.
* The Chi-squared formula measures how far the observed counts deviate from what we would expect if there was **no relationship**:

  $$
  χ² = \sum \frac{(Observed - Expected)^2}{Expected}
  $$

---

### 5. Real-World Applications

* **Healthcare**: Check if a treatment works better than another.
* **Marketing**: See if buying habits depend on customer age groups.
* **Education**: Analyze whether test results depend on teaching methods.

---


