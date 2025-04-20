# Air-Quality-Prediction-in-Delhi

📌 **Overview**  
Forecast Delhi’s AQI using a regression pipeline on PM₂.₅, PM₁₀, NO, NO₂, NH₃, SO₂ & CO to empower policymakers with actionable insights.

📌 **Motivation**  
Delhi’s severe pollution—driven by traffic, industry & crop burning—demands data‑driven AQI forecasts for timely interventions.

📌 **Objectives**  
- 📍 Build & compare regression models for AQI prediction  
- 📍 Identify top‑performing algorithms  
- 📍 Deliver insights for targeted air‑quality policies  

📌 **Methodology**  
- **Data**: Historical AQI, pollutant levels & weather  
- **Preprocessing**: Impute gaps, engineer time features, scale & remove outliers  
- **Models**:  
  - K‑Neighbors (R² 0.9678)  
  - CatBoost (R² 0.9646)  
  - XGBoost (R² 0.9554)  
  - LightGBM (R² 0.9342)  
  - Bayesian Ridge (R² 0.7827)  

📌 **Key Insights**  
- Ensemble regressors excel (K‑Neighbors tops)  
- PM₂.₅, PM₁₀ & NO₂ most critical features  
- Distinct pollution clusters highlight when/where to act  

📌 **Contributors**  
- Shrey Yadav: Data collection & prep  
- Lakshay Trehan: EDA & preprocessing  
- Karanjeet Singh & Lakshay Trehan: Cleaning  
- Yash Singh & Sahil: Modeling & analysis  

📌 **Tech Stack**  
Python • scikit‑learn • XGBoost • CatBoost • LightGBM • pandas • matplotlib • seaborn

📌 **Future Work**  
- Ingest real‑time sensor feeds  
- Explore deep‑learning AQI models  

📌 **References**  
1. Mahanta et al., *Urban Air Quality Prediction…* (IEEE, 2019)  
2. Shukla et al., *Flexible Models for Photochemical Pollutants…* (Chemosphere, 2021)  
3. Kumar & Goyal, *Forecasting Air Quality in Delhi…* (Atmospheric Pollution Research, 2011)  
4. Gupta et al., *ML Techniques for AQI Prediction…* (JE Public Health, 2023)  
5. Ganesh et al., *Regression Models for AQI…* (IEEE, 2017)  
