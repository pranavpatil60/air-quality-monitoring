# Air Quality Monitor 🫧
A beginner-friendly project to **analyze and visualize air quality** data using Python.

## 🔧 Features
* Data loading and cleaning (handling missing values, fixing data types)
* Exploratory Data Analysis (EDA) with clear visualizations
* Correlation analysis (pollutants vs AQI)
* Multiple machine learning models for AQI prediction (Linear Regression, Ridge, Lasso, ElasticNet, Decision Tree, Random Forest, Gradient Boosting, XGBoost, SVR, KNN)
* Exportable plots and reports

## 📁 Project Structure
.
├── Air_quality.ipynb        # Main Jupyter Notebook  
├── data/                    # Raw datasets (ignored in .gitignore)  
├── README.md                # Project documentation  
└── reports/                 # Saved charts and results (optional)  

> Tip: Exclude `data/` and other large files from GitHub using `.gitignore`.

## ✅ Requirements
* Python 3.9+  
Install dependencies: `pip install -r requirements.txt`  
If `requirements.txt` is not available: `pip install jupyter pandas numpy matplotlib scikit-learn plotly xgboost`

## ▶️ How to Run
1. Clone or download this repository.  
2. (Optional) Create and activate a virtual environment:  
`python -m venv .venv`  
`source .venv/bin/activate      # Mac/Linux`  
`.venv\Scripts\activate         # Windows`  
3. Install dependencies (see above).  
4. Launch Jupyter Notebook: `jupyter notebook`  
5. Open `Air_quality.ipynb` and run the cells step by step.

## 📊 Data
* Input format: CSV files with pollutants such as **PM2.5, PM10, NO2, SO2, O3, CO, etc.**  
* Place your datasets inside the `data/` folder.  
* Update the file path in the notebook (e.g., `data/your_file.csv`).  
> If using a public dataset, add the source link here.

## 🧠 Modeling
Machine learning models applied for AQI prediction:  
Linear Regression, Ridge Regression, Lasso Regression, ElasticNet Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, XGBoost Regressor, Support Vector Regressor (SVR), K-Nearest Neighbors (KNN) Regressor.

### Model Evaluation Results
| Model                | R² Score | MSE      | Accuracy |
|---------------------|----------|----------|----------|
| Linear Regression    | 0.8081   | 2490.03  | 80.81%   |
| Ridge Regression     | 0.8081   | 2489.67  | 80.81%   |
| Lasso Regression     | 0.8085   | 2484.89  | 80.85%   |
| ElasticNet Regression| 0.8084   | 2486.56  | 80.84%   |
| Decision Tree        | 0.8829   | 1519.37  | 88.29%   |
| Random Forest        | 0.9318   | 884.51   | 93.18%   |
| Gradient Boosting    | 0.9277   | 938.07   | 92.77%   |
| XGBoost              | 0.9179   | 1065.25  | 91.79%   |
| SVR                  | 0.5343   | 6043.24  | 53.43%   |
| KNN Regressor        | 0.8190   | 2349.04  | 81.90%   |

## 📦 Results
* Key pollutants impacting AQI  
* Seasonal or temporal trends  
* City-wise comparisons  

All generated figures can be stored in the `reports/` folder.

## 🧪 Git Commands (for uploading to GitHub)
Initial setup:  
`git init`  
`git add .`  
`git commit -m "Initial commit: Air Quality Monitor"`  
`git branch -M main`  
`git remote add origin https://github.com/<your-username>/<your-repo>.git`  
`git push -u origin main`  

For updates:  
`git add .`  
`git commit -m "Update: Added EDA and ML models"`  
`git push`

## 🗂️ .gitignore (Recommended)
Environments: `.venv/`, `env/`, `*.env`  
Jupyter: `.ipynb_checkpoints/`  
Data & outputs: `data/`, `reports/`, `*.csv`, `*.xlsx`  
OS files: `.DS_Store`, `Thumbs.db`

## 🤝 Contributing
Contributions are welcome. Please open an issue or submit a pull request for suggestions and improvements.

## 📝 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## 🙏 Acknowledgements
* Open datasets on air pollution and AQI  
* Python open-source ecosystem (Pandas, NumPy, Matplotlib, scikit-learn, XGBoost, Plotly)

