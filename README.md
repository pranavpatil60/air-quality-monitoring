# Air Quality Monitor 🫧

A beginner-friendly project to **analyze and visualize air quality** data using Python.

---

## 🔧 Features

* Data loading and cleaning (handling missing values, fixing data types)
* Exploratory Data Analysis (EDA) with clear visualizations
* Correlation analysis (pollutants vs AQI)
* Multiple machine learning models for AQI prediction (Linear Regression, Ridge, Lasso, ElasticNet, Decision Tree, Random Forest, Gradient Boosting, XGBoost, SVR, KNN)
* Exportable plots and reports

---

## 📁 Project Structure

```plaintext
.
├── Air_quality.ipynb        # Main Jupyter Notebook
├── data/                    # Raw datasets (ignored in .gitignore)
├── README.md                # Project documentation
└── reports/                 # Saved charts and results (optional)
```

> Tip: Exclude `data/` and other large files from GitHub using `.gitignore`.

---

## ✅ Requirements

* Python 3.9+

Install dependencies:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:

```bash
pip install jupyter pandas numpy matplotlib scikit-learn plotly xgboost
```

---

## ▶️ How to Run

1. Clone or download this repository.
2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate      # Mac/Linux
   .venv\Scripts\activate       # Windows
   ```
3. Install dependencies (see above).
4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
5. Open `Air_quality.ipynb` and run the cells step by step.

---

## 📊 Data

* Input format: CSV files with pollutants such as **PM2.5, PM10, NO2, SO2, O3, CO, etc.**
* Place your datasets inside the `data/` folder.
* Update the file path in the notebook (e.g., `data/your_file.csv`).

> If using a public dataset, add the source link here.

---

## 🧠 Modeling

The following machine learning models were applied for AQI prediction:

* Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor
* Support Vector Regressor (SVR)
* K-Nearest Neighbors (KNN) Regressor

### Model Evaluation Results

🔹 **Linear Regression**
R² Score : 0.8081
MSE      : 2490.03
Accuracy : 80.81%
-----------------

🔹 **Ridge Regression**
R² Score : 0.8081
MSE      : 2489.67
Accuracy : 80.81%
-----------------

🔹 **Lasso Regression**
R² Score : 0.8085
MSE      : 2484.89
Accuracy : 80.85%
-----------------

🔹 **ElasticNet Regression**
R² Score : 0.8084
MSE      : 2486.56
Accuracy : 80.84%
-----------------

🔹 **Decision Tree**
R² Score : 0.8829
MSE      : 1519.37
Accuracy : 88.29%
-----------------

🔹 **Random Forest**
R² Score : 0.9318
MSE      : 884.51
Accuracy : 93.18%
-----------------

🔹 **Gradient Boosting**
R² Score : 0.9277
MSE      : 938.07
Accuracy : 92.77%
-----------------

🔹 **XGBoost**
R² Score : 0.9179
MSE      : 1065.25
Accuracy : 91.79%
-----------------

🔹 **SVR**
R² Score : 0.5343
MSE      : 6043.24
Accuracy : 53.43%
-----------------

🔹 **KNN Regressor**
R² Score : 0.8190
MSE      : 2349.04
Accuracy : 81.90%
-----------------

---

## 📦 Results

* Key pollutants impacting AQI
* Seasonal or temporal trends
* City-wise comparisons


---


## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request for suggestions and improvements.

---

## 📝 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 🙏 Acknowledgements

* Open datasets on air pollution and AQI
* Python open-source ecosystem (Pandas, NumPy, Matplotlib, scikit-learn, XGBoost, Plotly)
