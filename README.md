# Weekly_Assessment_2
# Weekly Assessment 2 – Pandas

## About the Assessment

This repository contains my **Weekly Assessment 2**, focused on understanding and applying important concepts of **Python Pandas**.

The assessment is divided into two sections:

* **Section A – Interview Theory**
* **Section B – Predict the Output**

The main focus is on understanding how Pandas works with data, missing values, indexing, transformations, and common DataFrame operations.

## Topics Covered

### Section A – Interview Theory

The assessment covers the following Pandas concepts:

1. **Series vs DataFrame**

   * Difference between one-dimensional Series and two-dimensional DataFrames
   * Methods applicable to both and DataFrame-specific methods

2. **`inplace=True`**

   * How it modifies Pandas objects
   * Why it is generally discouraged
   * Issues related to method chaining and `SettingWithCopyWarning`

3. **`fillna()` vs `dropna()`**

   * Replacing missing values
   * Removing rows or columns containing missing values
   * When to use each approach

4. **`pd.to_numeric()`**

   * Difference between normal conversion and `errors='coerce'`
   * Handling non-numeric values in real-world datasets

5. **`.loc` vs `.iloc`**

   * Label-based indexing
   * Position-based indexing

6. **`.map()` vs `.apply()` vs `.replace()`**

   * Mapping values
   * Applying custom functions
   * Replacing specific values

7. **`SettingWithCopyWarning`**

   * Why the warning occurs
   * How using `.copy()` can prevent the issue

8. **`pd.cut()` vs `pd.qcut()`**

   * Equal-width binning
   * Equal-frequency/quantile-based binning

## Section B – Predict the Output

The second section focuses on predicting and explaining the output of different Pandas operations.

The questions cover concepts such as:

* DataFrame references and object modification
* Handling `NaN` values in calculations
* Data type conversion using `pd.to_numeric()`
* Selecting rows from a DataFrame
* `SettingWithCopyWarning`
* Pandas `object` data type
* `nunique()`, `unique()` and `value_counts()`
* Boolean indexing and operator precedence

Each output prediction is accompanied by an explanation of why Pandas produces that particular result.

## Key Concepts Learned

Through this assessment, I worked on understanding:

* Difference between Pandas Series and DataFrames
* Handling missing and invalid data
* DataFrame indexing and selection
* Data type conversion
* Data transformation methods
* Pandas warnings and how to avoid common mistakes
* Binning and categorizing numerical data
* Difference between references and copies
* Behaviour of Pandas functions while handling `NaN` values
* Boolean filtering and operator precedence

## Technologies Used

* Python
* Pandas
* Jupyter Notebook / Google Colab

## Repository Structure

```text
Weekly-Assessment-2/
│
├── Weekly_assessment_2.ipynb
└── README.md
```

## How to Run

The notebook can be opened and executed using:

* Google Colab
* Jupyter Notebook
* JupyterLab
* VS Code with Jupyter support

To run it in Google Colab:

1. Open Google Colab.
2. Upload the `.ipynb` file.
3. Run the notebook cells.

## Learning Outcome

This assessment helped strengthen my understanding of **Pandas fundamentals** and improved my ability to predict the behaviour of Pandas operations instead of only relying on memorized syntax.

It also helped me understand some common issues that occur while working with real-world datasets, such as missing values, incorrect data types, chained assignments, and indexing.

## Conclusion

Weekly Assessment 2 provided practice with important Pandas concepts that are commonly used in data analysis and Python-based data science. The combination of interview questions and output prediction helped me focus on both **conceptual understanding and practical behaviour of Pandas operations**.

---

**Author:** Lakshmi Baj
