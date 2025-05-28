# 🌫️ Air Quality Index (AQI) Detection

This project focuses on predicting the **Air Quality Index (AQI)** value using machine learning models. The AQI provides a standardized way to report air pollution levels and understand potential health impacts. The model takes in various air quality parameters (like CO, Ozone, NO₂, PM2.5) and predicts the overall AQI value based on past data.
---

## 🧠 Project Workflow

### 1. Problem Definition
To predict the **AQI value** based on environmental and geographical parameters such as gas concentrations and AQI categories.

### 2. Exploratory Data Analysis (EDA)
- Checked for **missing values** and **duplicates**
- Imputed missing values using **forward fill**
- Visual inspection and distribution analysis of AQI components

### 3. Data Preprocessing
- Applied **Label Encoding** to convert categorical features (`Country`, `City`, AQI categories) into numerical format
- Prepared feature matrix `X` and target variable `y`

### 4. Model Building
Three regression models were trained and evaluated:
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Linear Regression**

Each model was evaluated using:
- **Training Score**
- **Testing Score**
- **R² Score** (Coefficient of Determination)

### 5. Model Evaluation
- All models were tested with actual data to predict AQI values
- Among the models, **Random Forest Regressor** provided the best performance and was chosen as the final model

### 6. Model Inference (Prediction)
- Simulated user input via command-line to test real-time AQI prediction
- Final AQI value predicted using trained model

### 7. Model Saving
- The best model can be saved using `joblib` or `pickle` for future use or deployment

---

## 📁 Project Structure

AQI-Detection/
├── dataset/
│ └── aqi_data.csv
├── aqi_prediction.ipynb
├── requirements.txt
└── README.md

## 📬 Contact

For any queries or suggestions, feel free to reach out:

- 📧 Email: [abineshbalasubramaniyam@example.com](mailto:abineshbalasubramaniyam@example.com)
- 💼 LinkedIn: [linkedin.com/in/abinesh-b-1b14a1290/](https://www.linkedin.com/in/abinesh-b-1b14a1290/)

