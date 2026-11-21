# FDS-PROJECT-COLLEGE-AREA-VEHICLE-RENTAL-590025445-
College Area Vehicle Rental Data Science Project using Python for data preprocessing, EDA, statistical analysis, visualization, feature engineering, hypothesis testing, PCA, Linear &amp; Logistic Regression, and predictive analytics.

#  College Area Vehicle Rental – Data Science Project

##  Project Overview

The **College Area Vehicle Rental Data Science Project** analyzes vehicle rental patterns in and around a college area using **Python, Statistics, Data Visualization, Feature Engineering, and Machine Learning**.

The project follows a complete data science workflow, beginning with data understanding and preprocessing and progressing through exploratory analysis, statistical testing, feature engineering, visualization, dimensionality reduction, optimization, and predictive modeling.

The main objective is to extract meaningful insights from vehicle rental data and develop models for **rental price prediction** and **recommendation acceptance prediction**.

---

##  Project Objectives

- Understand and explore vehicle rental data.
- Identify and handle missing values, duplicates, invalid values, and outliers.
- Perform descriptive and exploratory data analysis.
- Study vehicle demand, rental prices, customer ratings, weather, and traffic patterns.
- Apply probability and statistical concepts to real-world rental data.
- Perform hypothesis testing and ANOVA.
- Engineer useful features from existing attributes.
- Visualize important trends and relationships.
- Apply feature selection and dimensionality reduction.
- Implement optimization concepts using Gradient Descent.
- Build a **Linear Regression model** for rental price prediction.
- Build a **Logistic Regression model** for recommendation acceptance prediction.
- Evaluate machine-learning models using appropriate performance metrics.
- Generate data-driven insights useful for vehicle rental management.

---

##  Dataset

The project uses a **College Area Vehicle Rental Dataset** containing information about individual vehicle rental transactions.

Important attributes include:

- Rental Date
- Booking Time
- Student Year
- Vehicle Type
- Vehicle Model
- Pickup Location
- Drop Location
- Distance
- Duration
- Rental Price
- Payment Mode
- Weather
- Traffic Level
- Rental Purpose
- Customer Rating
- Vehicle Availability
- Demand Level
- Fuel/Battery Level
- Expected Duration
- Recommended Vehicle
- Recommended Route
- Recommendation Acceptance
- Cancellation Status

The dataset contains generated observations designed for educational data-science analysis.

---

##  Data Science Methodology

The project demonstrates concepts from standard data science methodologies.

### CRISP-DM

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

### SEMMA

1. Sample
2. Explore
3. Modify
4. Model
5. Assess

The overall project pipeline can be represented as:

**Data Collection → Data Cleaning → Exploration → Feature Engineering → Statistical Analysis → Visualization → Modeling → Evaluation → Insights**

---

##  Data Preprocessing

The preprocessing stage includes:

- Dataset structure inspection
- Data-type analysis
- Missing-value detection
- Missing-value treatment
- Duplicate detection and removal
- Text standardization
- Date and time conversion
- Numerical conversion
- Invalid-value handling
- Range validation
- IQR-based outlier detection

Potential outliers are identified using the **Interquartile Range (IQR)** method instead of being automatically removed, since unusually high rental prices may represent genuine car rentals.

---

##  Exploratory Data Analysis

The project performs EDA to understand important patterns in the rental system.

Analysis includes:

- Vehicle type frequency
- Demand-level distribution
- Average rental price by vehicle type
- Average customer rating by vehicle type
- Weather versus demand
- Distance versus rental price
- Rental trends over time
- Payment-mode distribution
- Rental-purpose distribution
- Customer-rating distribution

---

##  Descriptive Statistics

Important statistical measures are calculated, including:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Quartiles
- Interquartile Range
- Skewness
- Covariance
- Correlation

These measures help summarize the central tendency, variability, distribution, and relationships within the dataset.

---

##  Probability and Statistical Analysis

The project demonstrates probability concepts using actual rental observations.

Examples include:

- Probability of high demand
- Probability of a car rental
- Probability of recommendation acceptance
- Conditional probability of recommendation acceptance given high demand
- Empirical Probability Mass Function (PMF)
- Probability Density Function (PDF)
- Cumulative Distribution Function (CDF)
- Mathematical expectation
- Moments
- Binomial distribution
- Normal distribution
- Covariance and correlation

---

##  Sampling Distribution and Central Limit Theorem

The project demonstrates:

- Sampling distributions
- Bootstrap sample means
- Standard Error
- Central Limit Theorem
- Confidence Interval for population mean

A **95% confidence interval** is calculated to estimate the population mean rental price.

---

##  Hypothesis Testing

Statistical hypothesis testing is performed at a **5% significance level (α = 0.05)**.

The project includes:

- One-Sample t-Test
- Independent t-Test
- Approximate Z-Test
- F-Test
- Chi-Square Test of Independence
- One-Way ANOVA
- Two-Way ANOVA

The results are interpreted using the **p-value approach** to decide whether to reject or fail to reject the null hypothesis.

---

## Feature Engineering

New features are constructed from existing variables to improve analysis.

Engineered features include:

### Price per Kilometer

`Price_per_km = Rental Price / Distance`

### Average Speed

`Speed_kmph = Distance / Duration in Hours`

### Duration Difference

`Duration_Difference = Actual Duration - Expected Duration`

### Peak Hour

A binary feature indicating whether a rental occurred during selected peak hours.

---

##  Feature Selection

Feature subset selection is demonstrated to identify variables that are useful for predictive modeling.

This helps:

- Reduce unnecessary variables
- Simplify models
- Improve interpretability
- Reduce computational complexity

---

##  Dimensionality Reduction

**Principal Component Analysis (PCA)** is used to demonstrate dimensionality reduction.

PCA transforms correlated numerical variables into a smaller number of principal components while attempting to retain important information from the original dataset.

---

##  Optimization

The project demonstrates optimization concepts used in machine learning.

Topics include:

- Least Squares Optimization
- Gradient Descent
- Loss minimization
- Model parameter optimization
- Concept of constrained optimization
- Introduction to non-gradient optimization

Gradient Descent is demonstrated for estimating the parameters of a simple linear relationship.

---

##  Data Visualization

The project generates multiple visualizations using **Matplotlib** and **Seaborn**, including:

1. Vehicle Type Bar Chart
2. Rental Price Histogram
3. Rental Price Box Plot
4. Distance vs Rental Price Scatter Plot
5. Correlation Heatmap
6. Payment Mode Pie Chart
7. Daily Rental Trend Line Chart
8. Weather vs Demand Grouped Bar Chart
9. Average Price by Vehicle Type
10. Rental Purpose Distribution
11. Customer Rating Distribution
12. Rental Price by Demand Level
13. Actual vs Predicted Rental Price
14. Regression Residual Plot

These visualizations make important patterns and relationships easier to understand.

---

##  Machine Learning

### 1. Linear Regression

Linear Regression is used to predict **Rental Price**.

Example input features include:

- Distance
- Vehicle Type

Model performance is evaluated using:

- **MAE – Mean Absolute Error**
- **RMSE – Root Mean Squared Error**
- **R² Score**

The project also compares actual and predicted rental prices and analyzes regression residuals.

### 2. Logistic Regression

Logistic Regression is used as a classification algorithm to predict **Recommendation Acceptance**.

The model predicts whether a customer is likely to accept a vehicle recommendation.

Performance is evaluated using:

- Accuracy
- Confusion Matrix

---

## Types of Analytics Demonstrated

### Descriptive Analytics
Answers:

**“What happened?”**

Examples include rental counts, averages, distributions, and summary statistics.

### Diagnostic Analytics
Answers:

**“Why did it happen?”**

Correlation analysis, group comparisons, hypothesis testing, and ANOVA are used to investigate relationships.

### Predictive Analytics
Answers:

**“What is likely to happen?”**

Linear and Logistic Regression models are used for prediction.

### Prescriptive Analytics
Answers:

**“What should be done?”**

Analytical results and recommendation-related information can support vehicle selection, availability, and operational decisions.

---

## Technologies and Libraries

The project uses:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels

---

##  Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels
```

---

##  How to Run the Project

### Step 1

Clone the repository:

```bash
git clone <(https://github.com/aeshatech12/FDS-PROJECT-COLLEGE-AREA-VEHICLE-RENTAL-590025445-.git)>
```

### Step 2

Move into the project directory:

```bash
cd <FDS-PROJECT-COLLEGE-AREA-VEHICLE-RENTAL-590025445>
```

### Step 3

Keep the dataset in the same directory as the Python program:

```text
vehicle_rental_v3.csv
```

### Step 4

Run the Python program:

```bash
python vehicle_rental_full_syllabus.py
```

The graphs will appear one at a time. Close the current graph window to display the next visualization.

---

##  Suggested Repository Structure

```text
College-Area-Vehicle-Rental/
│
├── vehicle_rental_full_syllabus.py
├── vehicle_rental_v3.csv
├── README.md
├── requirements.txt
├── report/
│   └── Project_Report.pdf
└── images/
    └── project_visualizations/
```

---

## DataOps and MLOps Perspective

The project introduces the basic idea of:

**DataOps:** Managing reliable and repeatable data collection, preprocessing, transformation, and analysis pipelines.

**MLOps:** Managing machine-learning workflows involving model development, evaluation, deployment, versioning, and monitoring.

These concepts provide a connection between academic data science and real-world production systems.

---

##  Key Outcomes

This project demonstrates how a real-world vehicle rental problem can be studied through the complete data science lifecycle.

It combines:

**Data Collection → Data Cleaning → Statistical Analysis → EDA → Visualization → Feature Engineering → Optimization → Machine Learning → Model Evaluation → Decision Support**

The analysis can help understand rental behavior, demand patterns, pricing relationships, vehicle preferences, customer behavior, and recommendation acceptance.

---

##  Limitations

- The dataset contains generated observations for academic purposes.
- Results depend on the size and quality of the available dataset.
- The predictive models are intended primarily for educational demonstration.
- Additional real-world data would be required before deploying the models in a production vehicle-rental system.

---

##  Future Scope

The project can be extended by:

- Collecting real-time vehicle rental data
- Developing a web-based dashboard
- Integrating a relational or cloud database
- Adding real-time demand forecasting
- Comparing additional machine-learning algorithms
- Developing dynamic pricing models
- Adding route optimization
- Deploying models through APIs
- Implementing automated DataOps/MLOps pipelines
- Building a complete vehicle recommendation system

---

##  Academic Purpose

This project was developed as part of the **Fundamentals of Data Science** coursework to demonstrate practical implementation of data preprocessing, probability and statistics, exploratory data analysis, visualization, feature engineering, optimization, and introductory machine learning.

---

##  Author

**Aesha Chaudhary**  
**B.Tech CSE – Data Science**

---

## ⭐ Acknowledgement

This project demonstrates the practical application of concepts studied in **Fundamentals of Data Science** using Python and a vehicle rental use case.

If you find the project useful, consider giving the repository a ⭐.
