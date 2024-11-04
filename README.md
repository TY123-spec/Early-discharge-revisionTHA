**Predicting Early Hospital Discharge Following Revision Total Hip Arthroplasty**

This project analyzes and predicts early hospital discharge (EHD) outcomes following revision total hip arthroplasty (rTHA) using machine learning (ML) models. The study leverages data from the American College of Surgeons National Quality Improvement Program (ACS-NSQIP) database to identify patient and operative variables that predict EHD, providing insights that may improve patient selection and optimize resource allocation.

**Project Overview**

The primary objective of this study is to evaluate the effectiveness of ML models in predicting EHD for patients undergoing rTHA. The best-performing model, a Random Forest classifier, was cross-validated with traditional multivariable logistic regression (MLR) for comparison. The model identified the 10 most important variables associated with early discharge, including surgical indication, operative time, anemia status, anesthesia type, race, sex, functional status, BMI, age, and home support.

**Files Included**

The repository includes three primary files:

Python Code: A Python script to preprocess the data, train the model, and evaluate its performance.

JMP Script: An original script file designed to run within the JMP environment, connected to the NSQIP data.

Data Excerpt: An excerpt of the NSQIP dataset for demonstration purposes, containing anonymized sample data with variables relevant to predicting EHD. Due to privacy regulations, the complete NSQIP dataset is not included in this repository.

**Disclaimer**

This model is intended for research purposes only and should not be used to make clinical or surgical decisions. While the model demonstrates promising predictive capability for early discharge following revision total hip arthroplasty, external validation is required to confirm its accuracy and reliability in different patient populations and clinical settings. Please consult relevant healthcare professionals and undergo thorough validation before applying these findings in practice.
