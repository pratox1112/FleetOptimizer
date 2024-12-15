# FleetOptimizer

Overview

This project aims to optimize fleet operations by leveraging advanced data analytics, machine learning models, and geospatial data processing techniques. By analyzing real-world data such as pickup and dropoff times, locations, and trip durations, the project provides actionable insights to improve route planning, reduce costs, and enhance operational efficiency.

Key Features

Data Preprocessing: Cleaned and transformed raw fleet data to extract actionable features such as time-based and geospatial variables.

Geospatial Analysis: Utilized latitude and longitude differences to calculate distances and optimize route planning.

Feature Engineering: Created new variables including pickup hour, weekday, and trip duration in minutes for enhanced predictive modeling.

Machine Learning Models:

Trained models including Linear Regression, Decision Tree Regressor, and XGBoost for trip duration prediction.

Evaluated models using cross-validation and metrics like RMSE (Root Mean Square Error).

Visualization: Generated insightful plots to explore the distribution of trip durations and analyze operational patterns.

Dataset

The dataset includes:

Trip Details: Pickup and dropoff locations, times, and trip duration.

Geospatial Data: Latitude and longitude coordinates for each trip.

Operational Data: Store-and-forward flags, which indicate delayed dispatch.

Data used is from the NYC Taxi Trip duration dataset gathered from kaggle

Project Structure

Data Loading and Preprocessing:

Imported the raw dataset and handled missing values, duplicates, and data type conversions.

Engineered features such as pickup hour, weekday, and geospatial differences.

Exploratory Data Analysis (EDA):

Visualized trip duration distributions, patterns across time, and geospatial trends.

Model Development:

Trained and tested machine learning models including Linear Regression, Decision Tree Regressor, and XGBoost.

Evaluated models using metrics like RMSE and R-squared values.

Insights and Recommendations:

Provided actionable insights for optimizing fleet operations and reducing trip durations.

Results
The predictive maintenance system demonstrated effective performance in classifying machinery status into Normal, Maintenance Needed, or Emergency states. Key outcomes from the project include:

Error Metrics: The final predictive model achieved a Mean Absolute Error (MAE) of 4.37, reflecting its accuracy in predicting machinery states.

Model Performance: The combination of Random Forest, XGBoost, and Support Vector Machines, optimized using a genetic algorithm, ensured robust and reliable predictions, significantly reducing false positives and negatives.

Feature Insights: Feature extraction techniques, such as Recurrence Quantification Analysis and network-based metrics, played a critical role in capturing complex temporal patterns in acoustic signal data, enhancing the predictive accuracy.

Operational Impact: The implementation of this system led to an optimized maintenance schedule, reducing unexpected downtime and improving overall machinery reliability.

These results demonstrate the potential of combining advanced machine learning algorithms with domain-specific feature engineering to address critical operational challenges in predictive maintenance.
