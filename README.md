# Testing (Un)fairness in Personalized Machine Learning for Stress Detection in Ubiquitous Computing
> Alexia Ntantouri

This repository contains the code implementation of my BSc thesis titled **"Testing (Un)fairness in Personalized Machine Learning for Stress Detection in Ubiquitous Computing"** as part of my Bachelor's degree in Computer Science at Aristotle University of Thessaloniki (AUTh).

## Table of Contents
- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Requirements](#requirements)

## Overview
This thesis explores the potential of personalized machine learning (ML) models for stress detection using physiological data from wearable devices, focusing on the critical balance between accuracy and fairness

## Directory Structure
- `Final_CSVs/`: Contains the final datasets used in the analysis.
- `Images/`: Visualizations and figures used in the thesis.
- `Output_Files/`: Model outputs and result files.
- `Scored_Surveys/`: Survey results used to evaluate bias.
- `Thesis.pdf`: The final written thesis document.
- **Notebooks** For the LifeSnaps Dataset:
  - `LifeSnaps_Data_Bias.ipynb`: Data bias analysis for the LifeSnaps dataset.
  - `LifeSnaps_Model_Bias.ipynb`: Model bias analysis for the LifeSnaps dataset.
  - `LifeSnaps_User_Based_Splitting.ipynb`: User-based splitting models using the LifeSnaps dataset.
  - `LifeSnaps_Single_Attribute_Splitting.ipynb`: Single-Attribute splitting models using the LifeSnaps dataset.
  - `LifeSnaps_Multi_Attribute_Splitting.ipynb`: Multi-Attribute splitting models using the LifeSnaps dataset.
  - `LifeSnaps_Fuzzy_Clustering.ipynb`: Fuzzy clustering using the LifeSnaps dataset.
  - `LifeSnaps_Fuzzy_Splitting.ipynb`: Fuzzy splitting models using the LifeSnaps dataset.
- **Notebooks** For the SWELL-KW Dataset:
  - `SWELL_Data_Bias.ipynb`: Data bias analysis for the SWELL dataset.
  - `SWELL_Model_Bias.ipynb`: Model bias analysis for the SWELL dataset.
  - `SWELL_Generic_Model.ipynb`: Generic ML model using the SWELL-KW dataset.
  - `SWELL_User_Based_Splitting.ipynb`: User-Based splitting models using the SWELL-KW dataset.
  - `SWELL_Single_Attribute_Splitting.ipynb`: Single-Attribute splitting models using the SWELL-KW dataset.
  - `SWELL_Multi_Attribute_Splitting.ipynb`: Multi-Attribute splitting models using the SWELL-KW dataset.
  - `SWELL_Fuzzy_Clustering.ipynb`: Fuzzy clustering using the SWELL-KW dataset.
  - `SWELL_Fuzzy_Splitting.ipynb`: Fuzzy splitting models using the SWELL-KW dataset.

## Requirements
To run the notebooks, you'll need the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `fuzzy-c-means`
