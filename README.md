# California Housing Price Prediction

This project demonstrates an end-to-end workflow for performing Exploratory Data Analysis (EDA), preprocessing, model training, evaluation, and saving a machine learning model using the California Housing dataset from scikit-learn.

---

## **Project Overview**

The objective of this project is to predict median housing prices using multiple features such as:

* Median Income
* Average Rooms
* Average Bedrooms
* Population
* Latitude
* Longitude
* House Age

The workflow includes:

* Loading the dataset
* Converting it to a DataFrame
* Handling null values
* EDA (correlation, pairplots, boxplots)
* Feature scaling
* Training a Linear Regression model
* Model evaluation (MSE, MAE, R², Adjusted R²)
* Saving the trained model

---

## **Technologies Used**

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* Pickle (for saving the model)
* Jupyter Notebook / VS Code

---

## **Project Structure**

```
├── california_housing.ipynb
├── model.pkl
├── README.md
```

---

## **Code Summary**

### **1. Load and Prepare Data**

* Fetch California Housing dataset
* Convert to DataFrame
* Add price column

### **2. Perform EDA**

* Summary statistics
* Correlation heatmap
* Pairplots
* Boxplots for outliers

### **3. Preprocessing**

* Feature-target split
* Train-test split
* Standardization using `StandardScaler`

### **4. Model Training**

* Linear Regression
* Coefficient and intercept analysis

### **5. Model Evaluation**

Metrics used:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score
* Adjusted R² Score

### **6. Save the Model**

* Save using pickle for future use

---

## **Model Results**

The linear regression model yields:

* Lower MSE and MAE
* High R² value
* Adjusted R² calculated to account for feature count

This confirms the model's reasonable performance for predicting house prices.

---

## **How to Run the Project**

1. Clone the repository:

```
git clone <repo-url>
```

2. Install required libraries:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook or Python script.
4. View outputs in the console and visualizations.

---

## **Future Improvements**

* Train additional models (Random Forest, XGBoost)
* Hyperparameter tuning
* Feature engineering
* Outlier removal techniques

---

## **License**

This project is open-source and available under the MIT License.
