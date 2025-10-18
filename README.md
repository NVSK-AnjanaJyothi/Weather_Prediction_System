🌦️ Weather Prediction System
📘 Overview

The Weather Prediction System is a machine learning–based project that analyzes historical weather data to predict future weather conditions such as temperature, humidity, and pressure trends.
It helps visualize weather patterns and supports insights into climate variations using data analytics and predictive modeling.

📂 Dataset

The project uses the FDA1.csv dataset, which contains daily weather records with attributes such as:

Feature	Description
Date	Recorded date
Average temperature (°F)	Mean temperature of the day
Average humidity (%)	Mean humidity percentage
Average barometer (in)	Atmospheric pressure
Average windspeed (mph)	Mean wind speed
Rainfall for month (in)	Total rainfall in inches
Maximum/Minimum pressure	Pressure extremes for the day
diff_pressure	Difference between max and min pressure
Month	Extracted from date for seasonal analysis
🧠 Objective

Predict future weather parameters such as temperature and humidity.

Analyze relationships between weather factors (temperature, humidity, wind, pressure).

Visualize weather trends and anomalies across months or years.

⚙️ Tech Stack

Language: Python

Environment: Jupyter Notebook (.ipynb)

Libraries Used:

pandas → Data loading and preprocessing

numpy → Numerical computations

matplotlib, seaborn → Visualization

scikit-learn → Model building and evaluation

🚀 Features

Data cleaning and preprocessing of raw CSV weather data

Exploratory Data Analysis (EDA) with trend and correlation graphs

Machine Learning model training (e.g., Linear Regression, Decision Tree)

Prediction of future temperature or humidity

Model performance evaluation with metrics like R² Score and Mean Absolute Error (MAE)

🧩 Workflow

Data Collection: Load FDA1.csv dataset

Data Cleaning: Handle missing values and type conversions

Feature Engineering: Extract useful columns like month and pressure difference

Visualization: Plot trends and correlations between features

Modeling: Train predictive models (Linear Regression / Random Forest)

Evaluation: Compare predicted and actual values

Prediction: Generate forecasts for future weather conditions

📊 Example Visualizations

Temperature vs Humidity correlation heatmap

Monthly temperature and rainfall trends

Pressure vs Wind speed scatter plots

🧱 Challenges Faced

Handling incomplete or noisy data

Identifying the most significant features

Avoiding model overfitting with limited samples

Normalizing varying scales across features

🏁 Results

Accurate prediction of average temperature trends

Insightful visualizations highlighting seasonal variations

Improved understanding of atmospheric relationships

📌 Future Enhancements

Integrate live weather API data for real-time predictions

Deploy as a web application using Flask or Streamlit

Add deep learning models (LSTM) for time-series forecasting
