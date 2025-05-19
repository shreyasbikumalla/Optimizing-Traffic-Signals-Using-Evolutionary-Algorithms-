# 🚦 Traffic Signal Optimization using NSGA-II and MOEA/D

This project implements multi-objective evolutionary algorithms — **NSGA-II** and **MOEA/D** — to optimize urban traffic signal timings. The objective is to minimize vehicle **wait time** and **traffic congestion**, using either real-time traffic data or simulated urban traffic flow.

## 🔍 Overview

Modern cities face critical challenges with traffic congestion. Efficiently optimizing traffic signal timing can significantly improve traffic flow and reduce driver wait times. This project explores:

- **NSGA-II** (Non-dominated Sorting Genetic Algorithm II)
- **MOEA/D** (Multi-objective Evolutionary Algorithm based on Decomposition)

Both algorithms are applied to a traffic light control problem modeled with time-varying traffic inputs.

## 🧠 Algorithms Used

- **NSGA-II**: Uses non-dominated sorting and crowding distance to maintain a diverse set of Pareto-optimal solutions.
- **MOEA/D**: Decomposes a multi-objective problem into scalar sub-problems and optimizes them simultaneously.

## 📊 Objectives

- **Minimize average vehicle wait time**
- **Minimize total traffic congestion across intersections**

The system evaluates multiple traffic signal timings (phase durations) and returns optimal trade-off solutions.

## 📁 File Structure

```
.
├── 848 project code final.ipynb          # Main notebook with NSGA-II and MOEA/D implementation
├── 848 final code with result.ipynb      # Notebook showing final outputs (optional)
├── requirements.txt                      # Python packages required (optional)
└── README.md                             # This file
```

## 📈 Results

The results include:

- **Pareto front comparisons** between NSGA-II and MOEA/D
- **Wait time vs Congestion trade-offs**
- Visualizations for how different signal timings affect traffic flow efficiency

## 🔧 Requirements

Install required packages:

```bash
pip install numpy matplotlib pymoo pandas
```

You can also use the provided `requirements.txt` if available.

## ▶️ Running the Project

Simply open and run `848 project code final.ipynb` in a Jupyter Notebook environment (Google Colab or local Jupyter).

## 🔮 Future Enhancements

- Integrate with live traffic APIs (e.g., Google Maps or city IoT systems)
- Simulate larger intersections with real-time feedback
- Add additional objectives like fuel consumption or emissions
