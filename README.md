# Multispectral Mangrove Detection using Machine Learning 

This repository contains a complete Data Science and Machine Learning pipeline designed to detect and classify mangrove areas in Cartagena, Colombia, using multispectral satellite imagery (GeoTIFF). Developed as a degree project under a Research Seedbed program.

## Project Overview
The goal of this project is to automate the identification of mangrove ecosystems by processing multispectral bands (RGB + NIR) and applying advanced spectral analysis and machine learning algorithms. This approach transitions environmental monitoring from manual observation to data-driven spatial analysis.

## Technologies & Libraries
* **Language:** Python
* **Geospatial Processing:** Rasterio, Spectral Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (SVM, KNN, CART)
* **Visualization:** Matplotlib, OpenCV

## Methodology
1. **Data Preparation:** Extraction and normalization of RGB and NIR bands from a high-resolution GeoTIFF image.
2. **Feature Engineering:** Calculation of critical vegetation indices including NDVI, GNDVI, EVI, and OSAVI.
3. **Spectral Analysis:** Extraction of spectral signatures and threshold definition using Spectral Angle Mapper (SAM) and Spectral Differential Similarity (SDS).
4. **Model Training:** Pixel classification (Mangrove vs. Non-Mangrove) using Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Classification Trees (CART) with Stratified K-Fold cross-validation.

## Key Results
* Evaluated models using Accuracy, Precision, Recall, and F1-Score metrics.
* Generated highly accurate spatial detection maps, successfully isolating mangrove ecosystems from other land covers. 
