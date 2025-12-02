# 🏎️ F1 RaceIntel: Machine Learning–Powered Race Strategy Optimization

An end-to-end F1 analytics engine that predicts race outcomes, simulates strategy, and visualizes driver performance.

🚀 Overview

F1 RaceIntel is an advanced machine learning system designed to analyze Formula 1 race data and generate actionable race-strategy intelligence.
The project leverages lap-time telemetry, pit-stop metrics, driver performance patterns, and ML predictions to estimate finishing positions and identify the most optimal racing strategy.

This project demonstrates strong competence in:

✔ Feature engineering

✔ ML modeling (XGBoost, Random Forest, Logistic Regression)

✔ Data analysis & visualization

✔ Simulation systems

✔ Clean, modular software design

✔ Reproducible, industry-grade project architecture

This level of work aligns with expectations of Microsoft Student Programs, Data & Applied Science Internships, and Machine Learning roles.

🎯 Project Goals

Predict driver finishing positions using ML models

Quantify the effect of pit-stop strategies (0-stop, 1-stop, 2-stop)

Simulate a full race replay based on predicted positions

Create interactive and visual analytics for driver performance

Build a reusable and extendable race-strategy framework

🧠 Key Features
1️⃣ Intelligent Feature Engineering

Engineered a race-ready dataset including:

Average lap time

Lap-time standard deviation (consistency metric)

Lap pace deltas

Best & worst lap times

Total pit-stops & average pit duration

Driver points, historical performance

Clean indexing for race-driver mapping

These features capture driver skill, consistency, pace, and pit-efficiency—critical factors for predicting finishing positions.

2️⃣ Machine Learning Models

Implemented multiple ML approaches:

✔ XGBoost Regressor (Best Performer)

Achieved MAE ≈ 4.34

Tuned for racing-specific metrics

Handles nonlinear patterns in race data effectively

✔ Random Forest Regressor

✔ Logistic Regression (for position category classification)


3️⃣ Race Strategy Simulation Engine

A specialized module that tests the impact of race strategy choices:

Strategy	What It Does

0-stop	Assumes no pit penalties; fastest on paper

1-stop	Adds configurable pit penalty (e.g., +2.5s)

2-stop	Models aggressive pace with higher pit overhead

Outputs:

Predicted finishing position for each strategy

Strategy recommendation

Numerical & visual comparison

4️⃣ AI-Generated Race Replay (Lap-by-Lap Simulation)

Simulates a full race (50+ laps) to visualize predicted race flow:

Lap-wise driver positions

Driver trend lines

Heatmaps for position changes

Frame-by-frame output (GIF-ready)

This is a unique ML application that demonstrates system design beyond static predictions.

5️⃣ Driver Performance Insight Dashboard

Generated analytics include:

Pace stability (lap std deviation)

Pit efficiency

Best vs worst lap spread

Consistency ranking

Cumulative performance score

This mirrors real F1 analytics dashboards used by race engineers.
