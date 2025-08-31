# 🚲 Bike Sharing Demand Prediction

This project predicts the **demand for shared bikes** using the **BoomBikes dataset**.  
The goal is to help BoomBikes, a US bike-sharing provider, recover from a revenue dip during the COVID-19 pandemic by understanding the factors affecting bike demand and building a reliable predictive model.  

---

## 📌 Project Overview
- Built regression models to predict **daily bike rental demand**.
- Compared multiple algorithms:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluated models using **R² Score, RMSE, MAE, and Accuracy**.
- Best performance achieved with **Random Forest** (R² ≈ 0.90).

---

## 📊 Dataset
- Dataset: `boom_bikes.csv`,BoomBikes bike-sharing dataset(included in this repository).  
- Contains features such as:
  - Weather, Temperature, Humidity, Windspeed
  - Season, Year, Month, Holiday, Working Day
  - Bike demand (`cnt` column)

---

## 🛠️ Tech Stack
- **Language**: Python 3.x  
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`  
  - `jupyter`

---

## 📂 Repository Structure
Bike-Sharing-Demand-Prediction/

├── boom_bikes.csv                   # Dataset (included in repo)

├── Bike_Sharing_Demand_Prediction.ipynb   # Jupyter notebook with full workflow

├── requirements.txt                 # Python dependencies

├── README.md                        # Project documentation

└── .gitignore                       # Git ignore file


---

## ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Bike-Sharing-Demand-Prediction.git
   cd Bike-Sharing-Demand-Prediction
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Bike_Sharing_Demand_Prediction.ipynb

