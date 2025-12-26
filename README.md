# 🏎️ F1 RaceIntel — Machine Learning–Driven Race Strategy & Simulation

F1 RaceIntel is an end-to-end machine learning system that analyzes Formula 1 race data to **predict finishing positions**, **evaluate pit-stop strategies**, and **simulate full race replays** with data-driven visualizations.

The project combines feature engineering, ML modeling, strategy simulation, and analytics into a single reproducible pipeline.

---

## 🚀 Overview

Formula 1 race outcomes are strongly influenced by lap-time consistency, pit-stop strategy, and driver performance trends.  
F1 RaceIntel models these factors using historical race data to generate **actionable race-strategy intelligence**.

The system:
- Predicts driver finishing positions
- Simulates multiple pit-stop strategies (0-stop, 1-stop, 2-stop)
- Builds driver performance profiles
- Replays races using ML predictions
- Visualizes race dynamics and driver trends

All steps are orchestrated through `main.py`.

---

## 🧠 Core Capabilities

✔ Feature engineering from lap-time and pit-stop telemetry  
✔ Supervised ML model for finishing-position prediction  
✔ Strategy simulation with variable pit-stop counts  
✔ Driver performance profiling  
✔ AI-based race replay simulation  
✔ Advanced visualizations (heatmaps, lap trends, position evolution)  
✔ Modular, industry-style project architecture  

This project reflects expectations for **Machine Learning, Data Science, Sports Analytics, and Applied AI roles**.

---

## 📊 Data Sources

The system uses structured Formula 1 datasets including:

- Drivers and constructors
- Races and seasons
- Lap times
- Pit stops
- Results and standings
- Qualifying and sprint results

All data is stored locally as CSV files under the `data/` directory.

---

## ⚙️ Machine Learning & Strategy Modeling

- **Prediction Target**: Driver finishing position  
- **Model Type**: Regression-based ML model  
- **Input Features**:
  - Lap-time statistics
  - Pit-stop metrics
  - Engineered performance features  
- **Strategy Simulation**:
  - Evaluates 0-stop, 1-stop, and 2-stop strategies
  - Estimates finishing position impact for each strategy  

---

## 🔬 Race Simulation & Analytics

Beyond prediction, the system:

- Builds **driver profiles** from historical consistency and results
- Generates a **race replay matrix** using ML predictions
- Visualizes:
  - Lap-time trends
  - Pit-stop impact
  - Race heatmaps
  - Driver position trajectories over time  

This transforms raw ML output into interpretable race intelligence.

---

## 📈 Visualizations Included

- Lap-time performance plots  
- Pit-stop impact analysis  
- Race replay heatmaps  
- Driver position trend charts  

These visualizations help explain strategy outcomes and performance differences.

---

## 🛠 Tech Stack

- **Python**
- **Pandas / NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## ▶️ How to Run

### 1. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
