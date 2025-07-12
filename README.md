# Descriptive Analysis

This notebook contains the **Descriptive Analysis** portion of my Data Science internship, focused on understanding the structure and distribution of both **numerical** and **categorical** variables in a restaurant dataset.

---

## Task Objective

- Compute statistical summaries for key numerical columns
- Explore and interpret the distribution of categorical features like `Country Code`, `City`, and `Cuisines`
- Identify the most frequent cuisines and cities in the dataset

---

## Steps Performed

### 1. Numerical Analysis
Selected relevant numerical features:
- `Average Cost for two`
- `Price range`
- `Aggregate rating`
- `Votes`

For these, calculated:
- **Mean, Median, Standard Deviation**
- Used `.describe()` to generate percentiles, min/max, and spread

**Key Findings:**
- Cost and Votes are highly skewed (long-tail distribution)
- Most ratings lie between 2.5 and 4.0
- Median cost is ₹400; average is skewed due to some high-end entries

---

### 2. Categorical Analysis

#### a. Country Code
- 15 unique country codes
- Code `1` (India) appeared most frequently (8652 times)
- Created a mapping to actual country names using `.map()`

#### b. City
- 141 unique cities
- **New Delhi** had the highest number of restaurants (5473)
- NCR cities dominate the dataset

#### c. Cuisines
- 1825 unique cuisine combinations
- **North Indian** is the most common standalone cuisine (936 entries)
- Long-tail distribution with many unique/rare combinations

---

## 🔧 Tools Used
- Python
- Pandas
- Jupyter Notebook

---



