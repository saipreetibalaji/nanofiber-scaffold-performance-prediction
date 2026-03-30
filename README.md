# nanofiber-scaffold-performance-prediction
Endsemester project done along with my fellow teammates - Machine learning model to predict optimal nanofibrous scaffold configurations and healing time for skin tissue regeneration based on wound type and patient parameters.
# Nanofiber Scaffold Performance Prediction

## Overview

This project leverages machine learning to predict nanofibrous scaffold performance and wound healing time for skin tissue regeneration. It also incorporates an inverse design system to recommend optimal scaffold configurations based on desired healing outcomes and patient-specific parameters.

## Objectives

* Predict scaffold performance using machine learning models
* Estimate wound healing duration based on scaffold and patient data
* Design optimal scaffolds using inverse modeling
* Enable data-driven and goal-oriented tissue engineering

---

## Inverse Design System (Key Feature)

This project includes an inverse design module that predicts optimal nanofibrous scaffold configurations based on desired healing outcomes.

### Input:

* Target healing time
* Wound type
* Patient-specific parameters

### Output:

* Recommended scaffold properties (material, fiber diameter, porosity, etc.)

This enables a goal-driven approach to scaffold design rather than traditional trial-and-error experimentation.

---

## Dataset

The dataset includes:

* Scaffold properties (fiber diameter, porosity, material type, etc.)
* Fabrication parameters
* Patient-related features (wound type, severity, etc.)

### Target Variables:

* Healing time (in days)
* Scaffold performance metrics

## Methodology

### Data Preprocessing

* Handling missing values
* Feature scaling and normalization
* Encoding categorical variables

### Feature Engineering

* Dimensionality reduction using PCA
* ChemBERTa embeddings (for material representation, if applicable)

### Models Used

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

## Results

* Achieved high prediction accuracy (~98% for key targets)
* XGBoost demonstrated superior performance compared to other models
* PCA effectively reduced dimensionality while preserving model performance
* Successfully implemented inverse design system for scaffold recommendation

---

## Key Innovation

Unlike traditional approaches, this project integrates forward prediction with inverse design, enabling direct mapping from desired healing outcomes to scaffold configurations.

This bridges the gap between machine learning and practical biomedical scaffold design.

---

## Visualizations

* Correlation heatmaps
* PCA plots
* Feature importance graphs
* Prediction vs Actual comparisons

---

## Future Work

* Implement deep learning models for improved accuracy
* Develop an optimization-based inverse design engine
* Deploy as a web application (Streamlit/Flask)
* Expand dataset for better generalization

---
Done by -
B Sai Preeti 
Dishi Sharma
Nehasree J
Krithika

Your Name
(Add your GitHub / LinkedIn profile links here)
