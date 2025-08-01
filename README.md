# catalina-aiml
Repository for the AI/ML Class at UC Berkley

# README

## Coupon Acceptance Prediction Using Machine Learning 

## Overview

This Jupyter notebook explores the problem of **predicting whether a customer will accept a location-based coupon** using machine learning techniques. The project is built around a real-world use case: mobile coupons delivered based on a driver’s proximity and context (like time, companions, and destination).

We analyze various customer features to determine patterns in coupon acceptance behavior. The workflow includes data cleaning, exploratory data analysis (EDA), visualization, model building, and performance evaluation.

---

## Problem Statement

> Imagine driving through town and receiving a coupon on your phone for a nearby restaurant. Would you use it immediately, save it for later, or ignore it?  
>  
> This project aims to model customer behavior based on context—such as destination, weather, time of day, and passengers—to **predict coupon acceptance**.

---

## Key Steps and Highlights

1. **Data Import and Cleaning**
   - Loaded `coupons.csv` dataset
   - Checked null values and data types
   - Cleaned or converted columns where necessary (e.g., age group handling)

2. **Exploratory Data Analysis (EDA)**
   - Used `seaborn` and `matplotlib` to visualize:
     - Age distribution
     - Destination frequency
     - Impact of weather, companions, and time on coupon acceptance

3. **Feature Engineering**
   - Encoded categorical variables
   - Dropped irrelevant or redundant columns
   - Normalized data for model training

4. **Model Training**
   - Trained classification models including:
     - Logistic Regression
     - Decision Trees
     - Random Forests
     - Support Vector Machines
   - Evaluated models using metrics like accuracy, precision, recall, and F1 score

5. **Insights**
   - Determined the most important features influencing coupon acceptance (e.g., destination, time, passenger)
   - Compared model performance to select the best predictor

---

## Technologies Used

- Python 3.8+
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## How to Run

1. Clone this repo or download the notebook.
2. Ensure you have Python and dependencies installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook prompt.ipynb
   ```

---

## Author

Vinod Kasturi

## License

This project is licensed under the MIT License.
