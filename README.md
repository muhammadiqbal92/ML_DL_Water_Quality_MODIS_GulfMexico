# 🌊 Machine Learning & Deep Learning for Water Quality Monitoring using MODIS Aqua Data

This repository contains a complete workflow for analyzing and predicting water quality (chlorophyll-a concentrations) in the Gulf of Mexico using NASA MODIS Aqua satellite data. The project integrates machine learning and deep learning techniques, with a focus on environmental applications.

## 📌 Project Summary
This project demonstrates the use of MODIS Aqua chlorophyll-a data from Google Earth Engine (GEE), processed and modeled using Python, Random Forest, CNN, and LSTM architectures. Results show high prediction performance for identifying chlorophyll-a concentration trends—key indicators of algal blooms and water quality.

📄 [Read Full Report (PDF)](Muhammad%20Iqbal_Water%20Quality%20ML%20and%20DL%20Update.pdf)

## 📂 Repository Structure

```plaintext
.
├── app.py                            # Streamlit App for prediction
├── Application_of_MLDL_Water_Quality_MODIS_Aqua_Chlorophyll_a_(GEE).ipynb  # Main notebook
├── MODIS_ChlorA_Gulf_Mexico.tif     # GeoTIFF data from GEE
├── Water_Quality_Results.csv        # Sample prediction dataset
├── water_quality_model.pkl          # Random Forest model
├── lstm_water_quality.h5            # Trained LSTM model
├── cnn_water_quality.h5             # Trained CNN model
├── Muhammad Iqbal_Water Quality ML and DL Update.pdf  # Project Report
