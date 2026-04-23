# Study Time vs Exam Performance — Data Analysis

## Overview

This project explores the relationship between study time and academic performance using a simple data analysis pipeline.

The goal is to demonstrate how even small datasets can reveal meaningful patterns through visualization and interpretation.

---

## Research Question

How does the number of hours studied affect exam performance?

---

## Dataset

A synthetic dataset was created to simulate student behavior:

* **hours_studied**: number of hours spent studying
* **exam_score**: corresponding exam result

The dataset reflects a realistic positive correlation between effort and performance.

---

## Methodology

### Data Preparation

* Constructed dataset manually using Python
* Stored data in a Pandas DataFrame

### Visualization

* Used Matplotlib to create a scatter plot
* X-axis: study hours
* Y-axis: exam score

---

## Results

The scatter plot shows a clear **positive correlation**:

* As study time increases, exam scores also increase
* The relationship appears approximately linear

---

## Key Insights

* Increased study time generally leads to better performance
* Even a simple dataset can demonstrate strong trends
* Visualization is an effective tool for understanding relationships in data

---

## Limitations

* Dataset is synthetic (not real-world data)
* Small sample size (only 8 observations)
* Does not account for other factors:

  * sleep
  * stress
  * learning methods

---

## Future Work

* Collect real student data
* Apply regression models (Linear Regression)
* Add more variables (sleep, focus, environment)
* Perform statistical testing

---

## Tech Stack

* Python
* Pandas
* Matplotlib

---

## Conclusion

This project demonstrates a fundamental concept in data science: identifying relationships between variables using visualization.

While simple, it reflects the core workflow of real-world data analysis and provides a foundation for more advanced modeling.

---

## Author

Student project focused on data analysis, visualization, and foundational machine learning concepts.
