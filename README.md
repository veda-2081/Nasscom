# 🏠 House Price Prediction using Machine Learning

## 📌 Project Description

This project applies **machine learning techniques** to predict house prices based on various features such as number of rooms, location, fuel consumption, BMI, insurance data, etc. The goal is to train regression models using real-world data and evaluate them for accuracy and practical usability.

---

## 📊 Datasets Used

The following datasets were used for model training, analysis, and evaluation:

- `House prices dataset`
- `BMI_Analysis_V1.1.csv`
- `Claims_Practice_V1.0.csv`
- `Health_Ins_Expenses.csv`
- `MY2021_Fuel_Consumption_Ratings.csv`
- `RGRResults.csv`
- `Confusion Matrix V 2.0.xlsx`

> Note: Some of these datasets are for extended insights like health-insurance costs or vehicle fuel ratings, which may correlate with lifestyle or socioeconomic factors in house price prediction (if creatively integrated).

---

## 🧩 Features Engineered

- Location encoding
- Fuel efficiency as a proxy for socioeconomic status
- BMI and insurance expenses as potential lifestyle indicators
- Claims history and other numeric/categorical predictors

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Linear Regression, Ridge, Lasso, Random Forest, etc.)
- XGBoost / LightGBM (if used)
- Jupyter Notebook for EDA and model development

---

## 📈 ML Models Applied

- 🧮 Linear Regression  
- 🌲 Random Forest Regressor  
- 📉 Gradient Boosting Regressor  
- ✅ Model Evaluation: R², MAE, MSE, RMSE  
- 📊 Confusion Matrix (for classification-based comparisons)

---

## 📁 File Structure

```

├── BMI\_Analysis\_V1.1.csv                 # BMI data
├── Claims\_Practice\_V1.0.csv             # Insurance claim data
├── Confusion Matrix V 2.0.xlsx          # Classification metrics
├── Health\_Ins\_Expenses.csv              # Health expense features
├── MY2021\_Fuel\_Consumption\_Ratings.csv  # Fuel consumption proxy features
├── RGRResults.csv                       # Regression results
├── LICENSE                              # MIT License
├── README.md                            # Project overview
├── model\_notebook.ipynb                 # (Suggested name for the main notebook)

```

---

## 🔍 Exploratory Data Analysis

- Missing value treatment
- Outlier detection
- Correlation heatmaps
- Feature scaling & normalization

---

## 🔮 Prediction Goal

Given a new set of data entries, the trained model can predict:

> 💰 **Estimated house price** based on combined features.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for full details.

---

## 🙌 Contributions

Have suggestions or want to improve this project?  
Feel free to fork, clone, or submit a pull request.
