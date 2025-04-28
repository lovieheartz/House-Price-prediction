# 🏡 House Price Prediction - Linear Regression Project

This project implements **Simple** and **Multiple Linear Regression** using **Scikit-learn**, **Pandas**, and **Matplotlib** on a Housing Price Prediction dataset.

---

## 📌 Project Objectives
- Understand and implement Linear Regression (Simple & Multiple).
- Train and evaluate regression models.
- Visualize the predictions vs actual values.
- Improve the model using scaling and regularization (Ridge Regression).

---

## 📊 Dataset
The dataset used is **Housing.csv**, which includes various features affecting house prices such as:
- Area
- Bedrooms
- Bathrooms
- Mainroad Access
- Guestroom Availability
- Basement Availability
- Hot Water Heating
- Air Conditioning
- Preferred Area
- Furnishing Status (semi-furnished, furnished, unfurnished)

---

## 🛠️ Tools and Libraries
- **Python** 🐍
- **Pandas** 📚
- **NumPy** 🔢
- **Matplotlib** 📈
- **Seaborn** 🎨
- **Scikit-learn** 🤖

---

## 🧩 Project Workflow

### 1. Importing Libraries and Loading Data
- Loaded the `Housing.csv` dataset.
- Displayed initial records to understand the data structure.

### 2. Data Preprocessing
- Checked and handled missing values (if any).
- Encoded categorical variables like `mainroad`, `guestroom`, etc.
- Created dummy variables for `furnishingstatus`.

### 3. Train-Test Split
- Separated the data into Features (X) and Target (y).
- Split into 80% training and 20% testing sets.

### 4. Model Building
- Built a **Simple Linear Regression** model using `LinearRegression`.
- Trained and made predictions on the test set.

### 5. Model Evaluation
- Evaluated the model using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 6. Visualization
- Plotted **Actual vs Predicted Prices**.
- Created a **Residuals Distribution Plot** to check model bias.

### 7. Model Improvement
- Performed **Feature Scaling** using `StandardScaler`.
- Applied **Ridge Regression** to improve stability and performance.

---

## 📈 Key Results

| Metric               | Linear Regression | Ridge Regression |
|----------------------|--------------------|------------------|
| Mean Absolute Error   | Very Low           | Improved         |
| Mean Squared Error    | Very Low           | Improved         |
| R² Score              | High (~close to 1) | Slightly Higher  |

- The model performed **very well** on the test data.
- Ridge Regression slightly improved stability.

---

## 🔥 Visualizations
- **Actual vs Predicted Scatter Plot**
- **Residuals Distribution Plot**

These visualizations confirm the **good fitting** and **minimal bias** in the model.

---


