# 🏠 House Price Prediction using Linear Regression

##  Overview

This project focuses on predicting house prices using a Machine Learning approach.
I implemented a complete pipeline using **Linear Regression** to understand how different features (like area, bedrooms, etc.) affect house prices.

---

##  Objective

To build a regression model that can estimate house prices based on given input features and evaluate its performance using standard metrics.

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

##  Dataset

* Dataset: `Housing.csv`
* Contains features such as:

  * Area
  * Bedrooms
  * Bathrooms
  * Stories
  * Parking
  * Furnishing status
  * And more

---

##  Steps Performed

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Checked data types and missing values
* Understood feature distributions

---

### 2. Data Preprocessing

* Converted categorical values (yes/no) into numerical format
* Applied **one-hot encoding** for multi-category features
* Ensured all features are numerical

---

### 3. Feature Selection

* Used **all available features** except target (`price`)
* Defined:

  * `X` → input features
  * `y` → target variable

---

### 4. Feature Scaling

* Applied **StandardScaler**
* Normalized data to improve model performance

---

### 5. Train-Test Split

* Split data into:

  * Training set (80%)
  * Testing set (20%)

---

### 6. Model Training

* Used **Linear Regression (sklearn)**
* Trained model on training data

---

### 7. Prediction

* Predicted house prices on test data
* Generated predictions for new custom inputs

---

### 8. Model Evaluation

* Used:

  * Mean Squared Error (MSE)
  * R² Score

👉 **R² Score: 0.67**

* Indicates moderate performance
* Model captures general trend but has some variance

---

### 9. Visualization

* Plotted **Actual vs Predicted Prices** using scatter plot
* Observed:

  * Positive correlation
  * Some spread indicating prediction error

---

### 10. Bulk Predictions

* Generated predictions for **30 randomly created houses**
* Saved results into:

  * `30_house_predictions.csv`

---

## 📊 Results

* Model is able to capture relationships between features and price
* Performance is moderate due to linear assumptions
* Works well as a baseline model

---

##  Output Files

* `project.ipynb` → main implementation
* `training.ipynb` → experimentation
* `Housing.csv` → dataset
* `30_house_predictions.csv` → predicted results

---

##  What I Learned

* End-to-end Machine Learning workflow
* Importance of **data preprocessing and encoding**
* Feature scaling and its impact on model performance
* Handling **feature mismatch issues** in prediction
* How to evaluate regression models using R² and MSE
* Visualizing model performance using scatter plots
* Generating and exporting predictions to files
* Using GitHub to manage and present ML projects

---

##  Future Improvements

* Use advanced models like:

  * Random Forest
  * Gradient Boosting
* Perform feature engineering
* Hyperparameter tuning
* Deploy as a web app (Streamlit)

---

##  Conclusion

This project helped me understand the fundamentals of regression models and the complete ML pipeline, from data preprocessing to model evaluation and deployment-ready outputs.

---
