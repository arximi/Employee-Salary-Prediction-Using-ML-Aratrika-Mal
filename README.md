## Machine Learning Powered Employee Salary Prediction 

-This project aims to build a machine learning-powered web application that predicts an employee's **average salary** based on input features like experience, department, job rating, gender, country, and work center.
-The final app is built using **Streamlit** and trained using several machine learning algorithms.

## Project Summary

-The project leverages a cleaned and preprocessed dataset to develop various machine learning models and selects the best based on evaluation metrics like **MAE**, **RMSE**, and **accuracy**. 
-It helps to estimate analyze salary distribution across departments or locations.


## Features

- Trained on multiple ML models (Linear Regression, Decision Tree, Random Forest, etc.)
- Best-performing model automatically selected
- Salary analysis charts included for exploration
- User-friendly Streamlit interface for predictions
- Saves encoders and models for consistent deployment
- Visualizations of job rates, department-wise salaries, and more


## Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Streamlit (for web app)
- Matplotlib / Seaborn (for plots)
- Joblib (for model serialization)
- Ngrok (for running Streamlit apps on Colab or locally and exposing them with a public URL)

## Sample Input Fields
-Gender

-Department

-Country

-Center

-Years of Experience

-Job Rate

The app encodes these fields and predicts a fair annual salary based on trained ML models.

## Future Scope
-Deploy on Streamlit Cloud with a permanent URL

-Integrate database for live employee records

-Add authentication for internal HR use

-Explore neural network models for improved accuracy





