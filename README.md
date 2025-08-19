#  Predeicting High Booking Properties on Airbnb with Machine Learning (R Project)

## Project Overview
This project focuses on identifying **properties which will achieve a high booking rate** using machine learning techniques in **R**.  
The goal was to analyze what factors drives high booking rates and build predictive models that could assist potential investors in identifying properties which would be a good investment.

- **Dataset:** Kaggle Airbnb dataset (Cannot Disclose).  
- **Objective:** Develop models that predict high booking rate properties based on listing features.  
- **Deliverables:** Exploratory analysis, predictive models, evaluation metrics, final report.

---

## Tech Stack
- **Language:** R  
- **Libraries:** `tidyverse`, `caret`, `missForest`, `ggplot2`, `xgboost`, `glmnet`, `readr`, `dplyr`, `stringr`, `purrr`, `mice`       
- **Tools:** RStudio, RMarkdown  

---

## Workflow
1. **Data Cleaning & Preparation**
   - Handled missing values and outliers.
   - Encoded categorical variables (e.g., neighborhood, room type).
   - Feature engineering (e.g., host experience, amenities count).

2. **Exploratory Data Analysis (EDA)**
   - Visualized key factors affecting price (location, room type, reviews).
   - Identified skewness and applied transformations where necessary.

3. **Modeling**
   - Baseline: Linear Regression.  
   - Advanced: Random Forest, XGBoost, Catboost, LightGBM.  
   - Hyperparameter tuning via cross-validation.

4. **Evaluation**
   - Metrics: AUC.  
   - Compared models to select best-performing approach.

---

## Results
- **Best Model:** XGBoost (91% Accuracy).  
- **Key Predictors:** Location (latitude/longitude), room type, number of reviews, availability.  
- **Business Insight:** Location and property type dominate pricing power, while host reputation contributes marginally.  

---

## Repository Structure
