✈️ Flight Delay Duration Prediction
Overview

Flight delays not only frustrate air passengers and disrupt travel plans, but also generate significant operational and financial costs for airlines. These impacts include reduced efficiency, increased capital costs, aircraft and crew reallocation, and additional crew-related expenses. Over time, frequent delays may also negatively affect passenger demand and airline reputation.

This project addresses these challenges by building a machine learning model to predict the estimated duration of flight delays per flight.

🎯 Objective

The objective of this project is to accurately predict flight delay durations using historical flight data. 
Reliable predictions can help airlines, airports, and other stakeholders anticipate disruptions, optimize resources, and reduce time, cost, and operational losses.

📊 Dataset

The project uses datasets provided by the competition:

Train dataset: historical flight data with observed delay durations (target variable)

Test dataset: flight data without delay labels, used for final prediction

The final predictions are stored in a submission file, formatted according to the competition requirements.

🧠 Methodology : Machine learning regression models  used 

* Random Forest

* Gradient Boosting

* XGBoost

* LightGBM

📈 Evaluation Metric
Root Mean Squared Error (RMSE)

[RMSE measures the average magnitude of prediction errors and penalizes large deviations, making it suitable for estimating flight delay durations.]

🚀 Conclusion

This project demonstrates the application of machine learning techniques to a real-world aviation problem. 
Predicting flight delay durations can support data-driven decision-making and help mitigate the negative impacts of delays on both airlines and passengers.
