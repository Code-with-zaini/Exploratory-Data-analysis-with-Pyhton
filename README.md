
# 📊 Exploratory Data Analysis (EDA) Labs – Car & Laptop Datasets

This repository contains my exploratory data analysis (EDA) labs, where I worked with real-world datasets (cars and laptops) and applied various **statistical and visualization techniques** to uncover relationships between features and the target variable (price).

---

## 📂 Contents

* `Expolatory_data_analysis_Car.ipynb` → EDA on automobile dataset.
* `Expolatory_data_analysis_Laptop.ipynb` → Hands-on EDA lab on laptop pricing dataset.
* `README.md` → Project documentation.

---

## 📊 Dataset Descriptions

### 🚗 Car Dataset

Notebook(s): `Expolatory_data_analysis_Car.ipynb`, 

* Attributes include: make, drive-wheels, body-style, engine-size, horsepower, price, etc.
* Use case: Useful for understanding relationships between car attributes and price, and identifying key predictors for price modeling.

### 💻 Laptop Dataset

Notebook: `Expolatory_data_analysis_Laptop.ipynb`

* Attributes include: Brand, Category, GPU, OS, CPU\_frequency, CPU\_core, RAM\_GB, Storage\_GB\_SSD, Screen\_Size\_inch, Weight\_pounds, Price, etc.
* Use case: Analyzing how specifications (CPU, GPU, RAM, etc.) affect laptop pricing, identifying significant predictors, and comparing product categories.

---

## 🛠 Techniques Applied

1. **Descriptive Statistics**

   * Used `.describe()`, `.value_counts()`, and summary statistics.
   * Helped to understand data distribution, quartiles, mean, standard deviation.

2. **Visualization of Features**

   * **Boxplots**: To compare price distributions across categories like drive-wheels, GPU, OS.
   * **Scatter plots & Regression plots**: To visualize relationships between continuous variables (e.g., engine-size vs price, CPU\_frequency vs price).

3. **Grouping & Pivot Tables**

   * Used `groupby()` and `pivot()` to explore combinations of categorical variables (e.g., drive-wheels + body-style, GPU + CPU\_core) and their effect on average price.
   * Visualized with heatmaps for easier interpretation.

4. **Correlation Analysis**

   * Calculated Pearson correlation coefficient (`stats.pearsonr`) and p-values.
   * Identified which numerical variables (engine-size, horsepower, CPU\_frequency) had the strongest relationship with price.

5. **Outlier Detection with Boxplots**

   * Applied IQR-based fences (1.5 × IQR rule) to identify extreme values.
   * Visualized outliers as points outside boxplot whiskers.

---

## 🚀 Applications of These Techniques in Real-World Projects

Car dataset techniques:

* Price prediction models (linear regression, multiple regression).
* Feature importance analysis (which attributes affect price most).
* Market insights into vehicle categories and customer segments.

Laptop dataset techniques:

* Product comparison based on price vs specifications.
* Identifying key factors (CPU, GPU, RAM) driving laptop prices.
* Laying the foundation for recommendation systems and prediction models.

---

## 🧰 Tools & Libraries

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

## 🔑 Learning Outcomes

Through these EDA labs, I gained hands-on experience with:

* Summarizing data using descriptive statistics.
* Visualizing categorical and continuous variables.
* Using groupby and pivot tables for multi-feature analysis.
* Measuring relationships with Pearson correlation.
* Detecting outliers and understanding their impact.

---

## 📌 Notes

* Car dataset is analyzed in `Expolatory_data_analysis_Car.ipynb`.
* Laptop dataset is analyzed in `Expolatory_data_analysis_Laptop.ipynb`.
* These labs are part of my **Data Science coursework (Coursera – IBM Data Analysis with Python, Module 3: EDA)**.

