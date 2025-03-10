# predictive-maintenance-system

A POC on how engine data can be used to predict the maintainance status of vessels at PSA Marine using a Kaggle dataset. Task: using the given features like coolant presssure and fuel pressure, predict whether the engine needs maintainance (binary classification).

## Features Correlation matrix
This plot shows that the features have low correlation with each other, showing feature independence. As such, each feature will be a great addition for the modelling of this task.

![Correlation Matrix](imgs/features_correlation_matrix.png)


## EDA on features
## Histogram of Engine RPM

![hist_engine_rpm](imgs/hist_engine_rpm.png)

## Boxplot of Engine RPM

![boxplot_engine_rpm](imgs/boxplot_engine_rpm.png)


## Model results
Trained 4 different models. Results summarised below. A 65% accuracy is reasonable for real-world predictive maintenance due to sensor noise, data imbalance, and complex engine dynamics. Despite not being perfect, it still provides valuable insights, enabling proactive maintenance and reducing unplanned downtime. Given the challenges of real-world data, this level of accuracy can effectively support decision-making and improve operational efficiency. 🚀

![predictive_maintainance_results](imgs/predictive_maintainance_results.jpg)
