# Crime Hotspot Analysis using Machine Learning & GIS
## This project analyzes crime data to identify spatial and temporal hotspots using Random Forest Classification and advanced GIS techniques. It combines Python-based machine learning with ArcGIS Pro for geospatial visualization.

## 📌 Overview
The goal of this project is to:
-Clean and preprocess crime incident data.

-Extract time-based features (year, month, hour).

-Predict whether a location is a hotspot using machine learning.

-Visualize and map results in ArcGIS Pro for deeper spatial analysis.

## 🛠️ Tech Stack
-Python (Jupyter Notebook) – Data cleaning, feature extraction, machine learning.

-pandas & NumPy – Data processing.

-scikit-learn – Random Forest classification.

-Matplotlib & Seaborn – Statistical visualization.

-ArcGIS Pro – Spatial analysis, hotspot mapping, Kernel Density Estimation (KDE).

-Kriging Interpolation – For spatial prediction of crime intensity.

## 📂 Dataset
-The dataset (CrimeData.csv) contains:

--Latitude & Longitude – Geospatial coordinates of incidents.

--Date – Timestamp of the incident.

--LocationDescription – Type of location where the incident occurred.

--Arrest – Whether an arrest was made.


Link to dataset: https://www.kaggle.com/datasets/econdata/chicago-city-crime-dataset?resource=download

## 🔍 Workflow
-Data Cleaning

-Remove null coordinates.

-Convert date strings to datetime format.

-Extract Year, Month, and Hour fields.

-Feature Engineering

-Classify hotspot locations based on high-crime areas (e.g., streets, residential yards).

-Machine Learning

-Train a Random Forest Classifier to predict hotspots.

-Visualization

-Python: Actual vs predicted hotspot bar charts, distribution plots.

-ArcGIS Pro: Kernel Density Estimation (KDE), Kriging heatmaps, and spatial clustering.

## Output

Predictions saved as predicted_hotspots.csv for further GIS mapping.

## Python Visualization:
<img width="813" height="583" alt="image" src="https://github.com/user-attachments/assets/d33029dc-e8ff-4c21-b9a1-10910be6567e" />
<img width="781" height="561" alt="image" src="https://github.com/user-attachments/assets/6d87dd1e-4b93-45ea-9f84-a6dc89249808" />

## ArcGIS Pro Kernel Density Map:
<img width="594" height="516" alt="image" src="https://github.com/user-attachments/assets/e377f1da-6902-41e8-a6bf-f9ee30a9da22" />


## ArcGIS Pro Getis Ord (Hotspot Analysis) Map:
<img width="665" height="596" alt="image" src="https://github.com/user-attachments/assets/a6cf0a57-3d33-4363-962c-2b8b83bf08a4" />


## ArcGIS Pro Kriging Map:
<img width="482" height="455" alt="image" src="https://github.com/user-attachments/assets/34216cd0-93ba-4cba-8125-995e43d7e2d1" />
<img width="115" height="160" alt="image" src="https://github.com/user-attachments/assets/95bf37be-ec33-4e09-a4f1-ed5ea015da31" />


## Overlay of Kriging and Getis Ord (Hotspot Analysis)
<img width="674" height="597" alt="image" src="https://github.com/user-attachments/assets/5e0100f9-4e9a-4809-918e-6e1a8d52d2f7" />


## 🚀 How to Run
### Clone the repository:
```
git clone https://github.com/yourusername/crime-hotspot-analysis.git
```
### Install dependencies:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```
Place your dataset (CrimeData.csv) in the project folder.
Open the notebook in Jupyter Lab and run all cells.
Import predicted_hotspots.csv into ArcGIS Pro for spatial mapping.

## 📈 Future Improvements
-Integrate real-time crime data feeds.

-Deploy an interactive Web GIS hotspot dashboard.

-Add socio-economic and demographic layers for multi-factor analysis.

## What is avaliable in this repository:
-Report
-Jupyter Notebook (.ipynb)
-ArcGIS Pro Project File
-Presentation
-Predicted hotspot csv

## 📜 License
MIT License – Free to use, adapt, and share.
