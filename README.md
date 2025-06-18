# 🌾 Crop & Fertilizer Data Analysis

This project analyzes agricultural data to understand ideal crop growing conditions and fertilizer recommendations. It uses two datasets:
1. `crop_recommendation.csv` – data on crop requirements (N, P, K, temperature, humidity, pH, rainfall).
2. `fertilizer_prediction.csv` – data linking soil and crop types with suggested fertilizers.

## 📊 Project Steps
1. **Import libraries** – pandas, matplotlib, seaborn.
2. **Load datasets** from `data/`.
3. **EDA on Crop Data** – pair plots, correlation matrix, crop distributions.
4. **EDA on Fertilizer Data** – fertilizer usage distribution, nutrient histograms.
5. **Generate Summary** – average growing conditions for each crop.
6. **Save summary** to `output/avg_crop_conditions.csv`.

## 📁 Folder Structure
Crop-Fertilizer-Analysis/
│
├── data/
│ ├── crop_recommendation.csv
│ └── fertilizer_prediction.csv
│
├── output/
│ └── avg_crop_conditions.csv
│
├── crop_analysis.ipynb # Original notebook
├── crop_analysis.py # Converted Python script
├── README.md
└── requirements.txt

## 🛠 Requirements
See `requirements.txt`.

## 📌 Results
- Average values for temperature, pH, and nutrients for each crop.
- Visuals showing correlations and nutrient distributions.
- Distribution of recommended fertilizers.

## ✅ Status
Analysis complete. Ready for model building or dashboard visualization.
