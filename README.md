Opponent Weakness Analysis 🔍

Overview

This project analyzes cricket team weaknesses and provides strategic recommendations using AI models. It leverages decision trees and neural networks to predict match outcomes and generate strategies for captains and coaches based on historical performance data.

Features

Opponent Weakness Identification: Analyzes team performance under different conditions and against specific bowlers.

Machine Learning Models: Utilizes Decision Trees and Neural Networks for prediction.

Strategy Recommendations: Suggests the best players to counter opponents.

Winning Probability Estimation: Predicts the probability of winning against an opponent based on historical data.

Dataset

The dataset contains detailed player statistics with the following columns:

team, opposition_team, venue, match_outcome

runs, balls_faced, fours, sixes, strike_rate

wickets, overs_bowled, balls_bowled, runs_conceded, economy

catches, run_outs, maiden, stumps, fantasy_points

Installation

Prerequisites

Make sure you have Python and required libraries installed:

pip install pandas numpy tensorflow scikit-learn

Usage

Prepare the dataset

Place the dataset (odi_extended_dataset.csv) in the project directory.

Run the script

python opponent_weakness_analysis.py

Enter Player Matchups

Input multiple player-opponent pairs for strategy analysis.

View Strategy & Winning Probability

The script will output recommended strategies and winning probabilities based on the model predictions.

Model Details

Decision Tree Classifier for initial predictions.

Neural Network (MLP) for probability estimation of match outcomes.

Feature Scaling using StandardScaler.

Categorical Encoding for teams and venues using LabelEncoder.

Contribution

Feel free to contribute by:

Enhancing the dataset with more features.

Improving model accuracy.

Adding visualization dashboards.

License

This project is licensed under the MIT License.

