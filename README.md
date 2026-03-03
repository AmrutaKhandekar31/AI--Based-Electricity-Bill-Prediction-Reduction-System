# AI--Based-Electricity-Bill-Prediction-Reduction-System

AI-Based Electricity Bill Prediction & Reduction System ⚡
This project implements a Machine Learning-driven approach to predicting monthly electricity bills based on units consumed. Beyond simple prediction, the system includes a Smart Recommendation Engine that analyzes usage patterns and suggests actionable steps to reduce energy consumption and lower costs.
🚀 Features
 * Predictive Modeling: Uses a Linear Regression algorithm to forecast electricity costs with high precision.
 * Performance Metrics: Achieved a high R^2 Score of 0.94, indicating a strong correlation between units consumed and the final bill.
 * Automated Usage Analysis: Features a threshold-based alert system:
   * High Usage: Triggers a list of energy-saving tips (e.g., LED upgrades, phantom load reduction).
   * Optimal Usage: Confirms if the consumption is within a healthy range.
 * Model Persistence: Uses Joblib to save the trained model for seamless deployment.
🛠️ Tech Stack
 * Language: Python 3.x
 * Environment: JupyterLab / Anaconda
 * Libraries: * Pandas & NumPy (Data Manipulation)
   * Scikit-Learn (Machine Learning & Evaluation)
   * Matplotlib (Data Visualization)
   * Joblib (Model Serialization)
📊 Dataset & Model Performance
The model was trained on a dataset of 500 entries.
 * Algorithm: Linear Regression
 * Mean Squared Error (MSE): 69897.67
 * R^2 Score: 0.9429
The visualization shows a very tight fit between the Actual Data (Blue) and the Predicted Values (Black line), confirming the model's reliability.
