# Predictive-And-Prescriptive-Maintenance-With-AI
This project is about assessing data-driven models for predictive and prescriptive maintenance of safety-critical systems using NASA turbofan jet engines as a case study.


Safety-critical systems, such as those in aviation, healthcare, and nuclear power, require effective 
maintenance strategies to ensure optimal performance and prevent catastrophic failures. 
Predictive and prescriptive maintenance models leveraging Artificial Intelligence (AI) and Data 
Science have gained traction in various industries, but applying these models to safety-critical 
systems presents unique challenges. These challenges include ensuring data quality, model 
accuracy, transparency, and the integration of AI with legacy systems, all of which are crucial for 
maintaining safety and reliability in these critical environments. This research investigates data-driven models for predictive and prescriptive maintenance of the NASA Turbofan Jet Engine, a 
safety-critical system. The study evaluates key metrics, including Root Mean Square Error 
(RMSE), Mean Absolute Error (MAE), and R-squared (R²), to assess the effectiveness and 
reliability of maintenance models. Regression models built with machine learning techniques such 
as Long Short-Term Memory (LSTM), LSTM with Convolutional Neural Network (LSTM+CNN), 
Transformer, XGBoost, Random Forest, and Decision Tree, are compared. The results show that 
the XGBoost model achieves the most accurate predictions, with the lowest test RMSE of 
approximately 31 and test MAE of 25, outperforming more complex deep learning models like 
LSTM (test RMSE 37, test MAE 29) and Transformer (test RMSE 44, test MAE 36). While the 
LSTM+CNN model has slightly higher errors, it demonstrates a stronger ability to capture complex 
patterns, reflected in its highest test R² of around 0.5. In contrast, the Decision Tree model 
performs poorly, with a test R² of -0.25, indicating a significant mismatch with the data. 
Additionally, the study developed prescriptive anomaly detection classifiers, with the XGBoost 
and Random Forest models achieving exceptional test data accuracy of 97.8% and 98.6%, 
respectively, in categorising engine health into high-risk, moderate-risk, and low-risk levels. These 
results enable proactive maintenance planning and resource allocation. This research provides 
valuable insights into the assessment and improvement of data-driven maintenance strategies 
for safety-critical systems, with the ultimate goal of enhancing their overall performance, safety, 
and reliability.
