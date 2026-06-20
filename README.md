# Phase 4 - Solution Implementation and Descriptive Analysis

## Project Information
- **Student:** Brayan Alejandro Aguirre Cubillos
- **Group:** 203018207_1
- **Instructor:** Maria Alejandra Varona Taborda
- **Course:** (203018207A_2202) – Data Analysis
- **Institution:** Universidad Nacional Abierta y a Distancia (UNAD)
- **Specialization:** Telecommunications Networks
- **Date:** June 2026

## Project Description
This repository contains the descriptive analysis of the **Smart Agriculture Dataset**, developed for Phase 4 of the Data Analysis course. The goal is to explore environmental and soil variables (soil type, growth stage, moisture index, temperature, and humidity) to understand the patterns behind irrigation decisions in agricultural IoT environments.

## Repository Contents
- `Phase_4__203018207_1_Alejandro_Aguirre.ipynb` — Main notebook with the full descriptive analysis.
- `cropdata_updated.csv` — Dataset used for the analysis (16,411 records).
- `README.md` — This file.

## Dataset
The dataset used is the **Smart Agriculture Dataset**, originally selected and justified in Phase 2. It contains 7 variables: `crop ID`, `soil_type`, `Seedling Stage`, `MOI`, `temp`, `humidity`, and `result`.

## Key Findings Summary
- Temperature and humidity are the dominant environmental drivers of irrigation needs.
- The irrigation outcome (`result`) is a three-class variable, not a simple binary decision.
- The soil moisture index (MOI) alone shows weak linear correlation with irrigation, but follows a consistent pattern across soil types.
- Wheat is the most represented crop in the dataset.

## Forum Collaboration Evidence
*pending upload evidence*

## Explanatory Video
*pending upload video*

## How to Run This Project
1. Open `Phase_4__203018207_1_Alejandro_Aguirre.ipynb` in Google Colab or Jupyter Notebook.
2. Upload `cropdata_updated.csv` to the session storage.
3. Run all cells sequentially.
