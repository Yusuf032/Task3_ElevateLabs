# Task3_ElevateLabs
# Linear Regression — House Price Prediction

## 📌 Objective

The objective of this task is to implement and understand **Simple and Multiple Linear Regression** using a housing dataset.
The goal is to predict house prices based on different property features and evaluate the model using regression metrics.

---

## 🛠 Tools & Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📂 Dataset

House Price Dataset (CSV)

The dataset contains various house attributes such as:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Furnishing Status
* Air Conditioning
* Main Road Access
* Price (Target Variable)

---

## 🔎 Steps Performed

### 1. Data Loading

* Uploaded dataset into Google Colab
* Loaded using Pandas `read_csv()`

### 2. Data Preprocessing

* Checked dataset structure and summary statistics
* Removed missing values
* Converted categorical features using one-hot encoding
* Applied log transformation on price to reduce skewness

### 3. Feature Selection

Used multiple independent variables:

```
area, bedrooms, bathrooms, stories, parking and encoded categorical features
```

### 4. Train-Test Split

* Split dataset into 80% training and 20% testing data

### 5. Feature Scaling

* Applied StandardScaler to normalize features

### 6. Model Training

* Implemented Multiple Linear Regression using Ridge Regularization

### 7. Prediction

* Predicted house prices on test dataset

### 8. Model Evaluation

Evaluated using:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* R² Score

---

## 📊 Results

| Metric   | Value         |
| -------- | ------------- |
| MAE      | ~1.12 Million |
| MSE      | ~2.29e12      |
| R² Score | ~0.55         |

---

## 📈 Visualization

Plotted **Actual vs Predicted Prices** to evaluate model performance.

* Points near diagonal line indicate good prediction
* Moderate scatter indicates real-world variability

---

## 🧠 Interview Questions

**1. What assumptions does linear regression make?**
Linearity, independence, homoscedasticity, normality of residuals, and no multicollinearity.

**2. How do you interpret coefficients?**
Coefficient shows change in target variable for 1 unit change in feature.

**3. What is R² score?**
Percentage of variance explained by the model.

**4. When prefer MSE over MAE?**
When large errors should be penalized more.

**5. How detect multicollinearity?**
Using correlation matrix or VIF.

**6. Simple vs Multiple Regression?**
Simple uses one feature, multiple uses several features.

**7. Can linear regression be used for classification?**
No, it predicts continuous values.

**8. What if assumptions are violated?**
Model becomes unreliable and inaccurate.

---

## 🏁 Conclusion

Multiple Linear Regression improved performance compared to simple regression, showing house price depends on multiple features.
The moderate R² score (~0.55) indicates real estate prices contain non-linear and real-world factors that linear regression cannot fully model.

---

## 👨‍💻 Author

Mohd Yusuf Khan
