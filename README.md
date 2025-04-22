# Dalbavancin

This repository accompanies the study:
“Predicting prolonged dalbavancin exposure using machine learning: a validated strategy for individualized redosing”.

The project aims to support individualized redosing decisions for dalbavancin therapy using machine learning (ML) models trained on simulated pharmacokinetic (PK) profiles.


Repository Contents:

data/: contains the simulated pharmacokinetic datasets for both D1/D8 and D1/D15 dosing regimens, as well as the MIC distributions used in the modeling.

scripts/: includes all R scripts used for data preprocessing, feature engineering, model training, and evaluation.
The script 03_model_training_D1D15_D35.R builds the classifier for a 1500 mg dosing on Day 1 and Day 15 (D1/D15), specifically classifying plasma concentrations at Day 35.
All other models (e.g., for Week 6, Week 7, or D1/D8) were developed following the same structure and methodology.

A link to the interactive Shiny app is also provided below.



