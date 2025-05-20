# 🏠 House Price Prediction using Regression Models

This project focuses on predicting housing prices using various regression techniques. Developed as part of our graduate coursework (INFO 5502), the analysis utilizes real-world housing data sourced from Zillow to train and evaluate multiple regression models. The objective is to understand how different features influence housing prices and to build models that can forecast prices with high accuracy.

---

## 📦 Dataset

- **Source**: Zillow (included as `zillow_house_data.csv`)
- **Size**: Approximately 10,000 entries
- **Features**: Includes property type, number of bedrooms/bathrooms, area, location, year built, and more.

---

## 🔍 Problem Statement

Given structured housing data, our goals are to:
- Identify key factors that influence house prices.
- Apply regression techniques to predict property values.
- Evaluate models based on performance metrics and interpretability.

---

## ⚙️ Technologies & Tools

- Python 3.x  
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- Environment: Jupyter Notebook

---

## 📊 Methodology

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables (One-Hot Encoding, Label Encoding)
   - Outlier detection and removal

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Price distribution analysis
   - Feature-wise scatter plots

3. **Model Building**
   - Linear Regression
   - Ridge & Lasso Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor

4. **Evaluation Metrics**
   - R² Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)

5. **Model Comparison & Tuning**
   - Hyperparameter tuning using GridSearchCV
   - Feature importance analysis

---

## ✅ Results

- **Best Performing Model**: Random Forest Regressor  
- **R² Score**: 0.89 on the test set  
- **Key Influential Features**: `sqft_living`, `location`, `bedrooms`, and `grade`

---

## 📁 Repository Structure

```
├── Final_forecasting.ipynb         # Main notebook with code & results
├── zillow_house_data.csv           # Dataset
├── Project report.pdf              # Detailed report and findings
└── README.md                       # Project documentation
```

---

## 📌 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/achyuthkumarmiryala/House-Price-Prediction-Regression.git
   cd House-Price-Prediction-Regression
   ```

2. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Final_forecasting.ipynb
   ```

---

## 👥 Author

**Achyuth Kumar Miryala**  
Master’s in Data Science | University of North Texas  
📍 Denton, TX  
📫 [achyuthkumar286@gmail.com](mailto:achyuthkumar286@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/) | [GitHub](https://github.com/achyuthkumarmiryala)

---

## 💡 Future Work

- Deploy as a Streamlit web application  
- Explore deep learning models (e.g., DNN regressors)  
- Integrate geospatial visualizations (e.g., Folium maps)  
- Enhance feature engineering and incorporate external datasets (e.g., crime rates, school ratings)

---

## 📜 License

This project is intended for academic use only. Please contact the author for permissions if you'd like to reuse or extend the work.

---

If you found this project insightful, feel free to ⭐ the repository or connect on [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/)!
