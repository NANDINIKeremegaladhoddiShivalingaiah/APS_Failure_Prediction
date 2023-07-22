# APS_Failure_Prediction

Problem statement :

The system in focus is the Air Pressure system (APS) which generates pressurized air that are utilized in various functions in a truck, such as braking and gear changes. The datasets positive class corresponds to component failures for a specific component of the APS system. The negative class corresponds to trucks with failures for components not related to the APS system.

The problem is to reduce the cost due to unnecessary repairs.

1. Importing necessary Libraries
2. Loading the Dataset
3. Checking for missing values
4. Checking for unique values in target variable
5. Plotting the distribution of all independent numerical variables
6. Model Training and Evaluation
7. Finding the best model
8. Conclusion:
   The best Model is XGBoost Classifier with 99.6% accuracy and cost of 2950
