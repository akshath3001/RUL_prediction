# RUL_prediction
## Overview
This repository contains a Python-based implementation of a Remaining Useful Life (RUL) prediction model for Insulated Gate Bipolar Transistors (IGBTs). The model is trained and validated using the NASA IGBT Accelerated Aging Dataset. Predicting the RUL of IGBTs is crucial for the maintenance and reliability of power electronics systems.

## Key Features
Data Preprocessing: Clean and preprocess the raw NASA IGBT dataset.  
Feature Engineering: Extract meaningful features from raw data.  
Machine Learning Models: Implement and compare different models for RUL prediction (e.g., RNN, PI-RNN, LSTM and PI-LSTM).  
Model Evaluation: Evaluate the models using metrics such as MSE and R².  
Visualization: Plot results to analyze model performance and data trends.  

## Dataset
The NASA IGBT Accelerated Aging Dataset can be downloaded from the following link:
[Download Dataset](https://drive.google.com/drive/folders/1kdrWGIBv9tk4RfqmBe2-XBqQW6oLoVec?usp=drive_link)

## Usage
1. Clone or Download the Dataset  Clone the dataset repository or manually download the dataset into a directory on your local machine.  
2. Update Dataset Path in Notebook  After cloning the dataset, ensure that the dataset path is correctly specified in the provided Jupyter notebooks under the Read Pickle Data section.
3. Run Notebook Sections Sequentially  
