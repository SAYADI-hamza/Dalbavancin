# Dalbavancin

This repository accompanies the study:
“Predicting prolonged dalbavancin exposure using machine learning: a validated strategy for individualized redosing”.

The project aims to support individualized redosing decisions for dalbavancin therapy using machine learning models trained on simulated pharmacokinetic profiles.


Repository Contents:

data/: contains the simulated pharmacokinetic datasets for both D1/D8 and D1/D15 dosing regimens, as well as the MIC distributions used in the modeling.

scripts/: includes all R scripts used for data preprocessing, feature engineering, model training, and evaluation.
The script Dalbavancin Dosing Classifier (Day 35 Classification).Rmd builds the classifier for a 1500 mg dosing on D1/D15, specifically classifying plasma concentrations at Day 35. All other models were developed following the same structure and methodology.

A link to the interactive Shiny app is also provided below.



