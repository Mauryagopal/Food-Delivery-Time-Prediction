# Food Delivery Time Prediction Model

## 📌 Project Overview

The **Food Delivery Time Prediction Model** aims to accurately estimate the time required to deliver food orders. Timely delivery is essential in the food industry to enhance customer satisfaction and streamline logistics. This machine learning-based model leverages various features—such as location, weather, and delivery partner details—to predict delivery durations more precisely.

---

## 📊 Methodology

### a) Data Collection
- Collected from a provided dataset containing:
  - Order details
  - Delivery location
  - City information
  - Delivery person data
  - Weather conditions
  - Actual delivery times

### b) Data Preprocessing
- **Data Cleaning**:
  - Handled missing values, outliers, and inconsistencies.
- **Feature Engineering**:
  - Extracted relevant features such as:
    - Delivery person's age and ratings
    - Location coordinates (latitude/longitude)
    - Time-related attributes (e.g., order hour, day of the week)

### c) Model Development
- Trained multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor

- Applied cross-validation to ensure model robustness.

### d) Model Evaluation
- Evaluated using key metrics:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R-squared (R²) Score**

---

## 🛠 Technologies Used

- **Programming Language**: Python  
- **Development Environment**: Jupyter Notebook  

---

## 📦 Python Libraries

- `pandas`  
- `numpy`  
- `scikit-learn`  
- `matplotlib`  
- `seaborn`  
- `xgboost`

---

## 📁 Project Files

| File/Folder                          | Description                                              |
|-------------------------------------|----------------------------------------------------------|
| `Food-Delivery-Time-Prediction-Using-Machine-Learning.ipynb` | Notebook for model training and evaluation             |
| `model.pkl`                         | Serialized trained model                                 |
| `scaler.pkl`                        | Scaler object used during preprocessing                  |
                              

---

## ✅ Results

- **Best Model**: XGBoost Regressor  
- **R-squared (R²) Score**: **0.82**  
- The model demonstrated strong predictive performance, accurately capturing variations in delivery times.

---

## 🚀 Future Improvements

- Incorporate real-time traffic and weather data for better accuracy.
- Include more delivery partner-related features like average speed or delivery history.
- Tune model hyperparameters and explore neural networks or ensemble models.
- Expand the dataset for broader city and regional coverage.

---

## 🙌 Acknowledgements

Thanks to the open data providers and the machine learning community for tools and documentation that made this project possible.


