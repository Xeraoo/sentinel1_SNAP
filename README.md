# Crozon Coastal Area Remote Sensing Analysis

This repository contains a detailed workflow for analyzing radar and raster data of the **French coastal region near Crozon**. The project focuses on processing SAR (Synthetic Aperture Radar) data to calibrate, correct, filter, and classify the area, yielding insights into coastal features and changes. Each step includes screenshots where necessary to illustrate the procedures.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Data Loading](#data-loading)
3. [Raster Subsetting](#raster-subsetting)
4. [Radiometric Calibration](#radiometric-calibration)
5. [Range-Doppler Terrain Correction](#range-doppler-terrain-correction)
6. [Speckle Filtering](#speckle-filtering)
7. [Image Export in dB](#image-export-in-db)
8. [Image Classification](#image-classification)

---

## Introduction

This project aims to process remote sensing data to analyze the coastal area around **Crozon, France**. The analysis utilizes radar data processing techniques such as calibration, terrain correction, and speckle filtering, ultimately preparing the data for classification.


## Data Loading

The initial step involves loading raster and SAR data of the Crozon coastal area into the analysis software (e.g., SNAP, QGIS). The data includes multi-temporal radar imagery that captures surface and terrain features relevant to coastal dynamics.

![image](https://github.com/user-attachments/assets/f9b536ea-3583-4bad-bcfb-4114c6577fea)


## Raster Subsetting

To focus on the Crozon region, a **subset** of the raster data is created. This reduces processing time and allows for targeted analysis of the desired area.

![image](https://github.com/user-attachments/assets/87557c25-252e-4899-825d-928b76649d79)


## Radiometric Calibration

Radiometric calibration adjusts the radar image for **sensor effects** and converts data into a standardized format (Sigma Naught) for accurate analysis.

![image](https://github.com/user-attachments/assets/6a9dbb8d-e84d-48a8-ba1e-fd294219e6c2)


## Range-Doppler Terrain Correction

Terrain correction is essential for georeferencing SAR data. Using the **Range-Doppler Terrain Correction** method, we adjust the radar imagery to accurately match geographical features, correcting for terrain-induced distortions.

![image](https://github.com/user-attachments/assets/ee680460-f61b-4900-811f-2ee8f106d693)


## Speckle Filtering

SAR images often contain speckle noise due to radar backscatter. Applying a **Speckle Filter** smooths the image while preserving key features, making it more interpretable.

![image](https://github.com/user-attachments/assets/1a6667da-8c7a-4579-bcad-c2487faf68d0)


## Image Export in dB

The calibrated, terrain-corrected, and speckle-filtered image is saved in **dB (decibel) units** to standardize radar backscatter values, aiding in further analysis and comparison.

![image](https://github.com/user-attachments/assets/183689b5-61b4-4f09-887e-2e7b155e1787)


## Image Classification

The final step involves classifying the processed image to distinguish various land cover types or surface features within the Crozon coastal area. This step enables effective monitoring and analysis of coastal changes.

![image](https://github.com/user-attachments/assets/360a647e-74cd-45dc-8746-fbcfd13aa32e)


This repository serves as a guide for geospatial analysts and students interested in SAR data processing and coastal area analysis. Each step is documented with accompanying screenshots for ease of understanding.
