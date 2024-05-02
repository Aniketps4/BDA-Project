# BDA-Project

Wind Turbine Power Prediction with PySpark and GBT
This project utilizes PySpark for distributed processing on a Hadoop cluster to predict wind turbine power generation using a Gradient Boosting Tree (GBT) model.

Project Goals:

Develop a model to predict wind turbine power output based on historical data.
Leverage PySpark's capabilities for efficient processing of large datasets.
Employ Gradient Boosting Trees for accurate power prediction.
Requirements:

Hadoop cluster
PySpark
Familiarity with Python and machine learning concepts
Data:

Historical wind turbine power generation data
Corresponding weather data (wind speed, direction, temperature, etc.)
Workflow:

Data Acquisition:
Gather wind turbine and weather data.
Data Preprocessing with PySpark:
Load data into PySpark DataFrame.
Handle missing values and outliers.
Engineer new features if necessary.
Feature Engineering:
Analyze relationships between power output and weather variables.
Create new features based on the analysis.
Model Training and Evaluation:
Split data into training and testing sets.
Train a GBT model using PySpark MLlib.
Evaluate model performance using metrics like RMSE.
Hyperparameter Tuning (Optional):
Optimize model performance by adjusting hyperparameters.
Outputs:

A trained GBT model for wind turbine power prediction.
Evaluation results indicating model accuracy.
Getting Started:

Install PySpark on your Hadoop cluster.
Prepare your wind turbine and weather data.
Follow the provided Python scripts (or write your own) to implement the workflow steps.
Train and evaluate your GBT model.
Further Enhancements:

Explore time series analysis techniques for improved prediction accuracy.
Integrate the model into a larger wind farm management system.
Note: This README provides a general overview. Specific implementation details may vary depending on your data and chosen tools.
