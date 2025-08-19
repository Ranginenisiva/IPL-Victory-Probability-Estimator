# IPL Win Predictor

## Overview
The IPL Win Predictor is a machine learning-based project that forecasts the outcome of Indian Premier League (IPL) cricket matches. Users can input match details, and the app predicts the probability of each team winning. This project aims to provide insights and predictions for cricket enthusiasts and analysts.

## Features
- Select batting and bowling teams.
- Choose the host city.
- Input target score, current score, overs completed, and wickets fallen.
- Get real-time win probabilities for both teams.

## Dataset
The project uses historical IPL match data obtained from Kaggle. Data includes:
- Match details (teams, cities, scores)
- Player statistics
- Deliveries and innings information

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (modeling)
- Streamlit (web app)
- Pickle (model serialization)
- Jupyter Notebook (analysis)

## Files in the Repository
- `app.py` – Streamlit application for predictions
- `IPL_Win_Prob.ipynb` – Exploratory data analysis and model building
- `team.pkl`, `city.pkl`, `model.pkl` – Preprocessed data and trained model
- `Data/` – Dataset files (CSV/Excel)
- `requirements.txt` – Required Python libraries

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Ranginenisiva/IPL-Victory-Probability-Estimator.git
   cd IPL-Victory-Probability-Estimator
Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py
