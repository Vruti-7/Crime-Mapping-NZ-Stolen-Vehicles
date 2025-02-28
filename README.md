# 🚔 Mapping Crime Dynamics in New Zealand: A Geospatial Analysis of Stolen Vehicles  

📌 **Project Overview:**  
This project analyzes vehicle theft trends in New Zealand using **geospatial analysis** and **machine learning models**.  
It integrates **police area boundaries and stolen vehicle data** to uncover patterns, predict theft likelihood, and support crime prevention.  

![Choropleth_Map1](https://github.com/user-attachments/assets/edc8712e-6e34-46c4-8691-34f6b2a46c3d)

📊 **Dataset Sources:**  
- **NZ Police Area Boundaries:** [Koordinates](https://koordinates.com/layer/105481-nz-police-area-boundaries-29-april-2021/)  
- **Stolen Vehicles (NZ Police 2023-2024):** [NZ Police Stolen Vehicles](https://www.police.govt.nz/)  

## ✨ Key Features  
✔️ **Data Cleaning & Preprocessing** 📊  
✔️ **Geospatial Mapping of Crime Hotspots** 🗺️  
✔️ **Time Series Forecasting (ARIMA, SARIMA, Exponential Smoothing, Prophet)** 🔍  
✔️ **Crime Prediction using Machine Learning (Decision Tree, Random Forest, XGBoost)** 🤖  
✔️ **Crime Prevention Strategy Recommendations** 🚨  

## 🛠 Technologies Used  
- **Python 🐍** – Data processing & machine learning  
- **Jupyter Notebooks 📓** – Interactive analysis  
- **Pandas & NumPy 📊** – Data manipulation  
- **Matplotlib, Seaborn & Plotly 🎨** – Data visualization  
- **Geopandas 🌎** – Geospatial analysis  
- **Scikit-learn 🤖** – Machine learning models  
- **Statsmodels & Prophet** – Time series forecasting  

## 🚀 Setup Instructions  

### 🔹 1. Install Dependencies  
Ensure **Python 3.11+** is installed, then run:  
```bash
pip install pandas numpy matplotlib seaborn geopandas plotly scikit-learn statsmodels prophet
🔹 2. Run the Jupyter Notebook
  -  jupyter notebook:  Firstly, ensure that the all datasets from the provided source is downloaded and loaded properly.
                        Open Final_Project7(Data Cleaning).ipynb and run all the cells to clean and prepare the dataset.
                        Open Final_project7(Data Visualization).ipynb to generate crime maps and analysis.
                        Open Final_project7(Prediction).ipynb to run machine learning models and forecasts.

## 📂 Project Structure
Crime-Dynamics-NZ-Stolen-Vehicles/
│── Final_Project7(Data Cleaning).ipynb # Data preprocessing
│── Final_project7(Data Visualization).ipynb # Geospatial visualization
│── Final_project7(Prediction).ipynb # Predictive modeling
│── Datasets/
│ ├── stolenvehicles1.csv
│ ├── stolenvehicles2.csv
│ ├── nz-police-area-boundaries-29-april-2021.shp
│ ├── stolenvechilesdf3(cleandata4_N_merged).csv
│ ├── stolenvechilesdf3(cleandata5_N_merged).csv
│ ├── ReadMe(for_datasets).docx

📊 Results & Insights
📌 Geospatial Analysis: Identified high-theft regions using police district boundaries.
📌 Time Series Forecasting: SARIMA & Exponential Smoothing showed the best accuracy.
📌 Machine Learning Predictions: XGBoost was the most effective in predicting stolen vehicle types.
📌 Crime Prevention Strategies: Recommended strategic policing and community interventions.

📌 Note
This project was developed as an academic capstone project, focusing on geospatial analysis and machine learning to analyze vehicle theft patterns in New Zealand.
It addresses data integration challenges, crime prediction, and law enforcement insights, aiming to enhance crime prevention strategies through data-driven decision-making. 🚔📊
