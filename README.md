
# Project Delay Prediction and Mitigation

This project presents a simple machine learning solution to predict project task delays and proposes a basic mitigation strategy using simulated project management data.

## Project Structure

project-delay-prediction/
│
├ SAMPLE DATA(Book2).csv          # Provided dataset
├ project_delay_prediction.ipynb  # Jupyter Notebook with full analysis
├ Visualization                   # charts for EDA and Mitigation
├ README.md                       # Project overview and instructions

## Problem Statement

- Predict whether a task will be delayed based on:
  - Risk Level
  - Priority
  - Hours Allocated
- Suggest a mitigation strategy using what-if simulation.

## Requirements

```bash
pip install pandas matplotlib seaborn scikit-learn jupyter

## How to Run

1. Open `project_delay_prediction.ipynb` in Jupyter Notebook
2. Run each section:
   - Data Cleaning
   - EDA
   - Model Training
   - What-If Simulation

## Key Features

- Logistic Regression model
- Delay prediction visualization
- What-if scenario to reduce delays
- Correlation heatmap

## Results

- Accuracy: 33%
- ROC-AUC: 50%
- Increased hours for high-risk tasks showed reduced delay probability

## by

Athul K. Baiju  
April 2025
