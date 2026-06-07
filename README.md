# Agentic AI-Based Dynamic Tariff Optimization for EV Charging Networks

Submitted for **Open Project 2026 — Society of Business, IIT Roorkee**

## Overview
Static ₹/kWh pricing in EV charging networks causes peak-hour congestion, charger underutilization, and revenue loss. This project builds an Agentic AI framework that dynamically optimizes tariffs in real time using large-scale charging session data.

## Datasets
- **ACN-Data** — 30,000+ sessions from Caltech/JPL (JSON to CSV)
- **UrbanEV ST-EVCDP** — 24,798 charging piles, 5-min interval data, Shenzhen

## Agent Architecture
- **Demand Prediction Agent** — Forecasts utilization, congestion probability, and charging load
- **Tariff Pricing Agent** — Surge pricing above 80% utilization, discounts below 30%
- **Monitoring & Learning Agent** — Tracks revenue, wait times, and pricing efficiency over time

## Deliverables
- **Notebook** — `Agentic AI-Based Dynamic Tariff Optimization.ipynb` — full pipeline from preprocessing to agent evaluation
- **Report** — `Agentic AI-Based Dynamic Tariff Optimization.pdf` — presentation deck with findings and business implications
- **Model Outputs** — `Output Csv files/` — scores, metrics, and ranking CSVs
- **Visualizations** — `Output images - findings/` — EDA charts and pricing simulation plots
- **Datasets** — `Datasets_OP'26_Analytics.zip` — raw data used for analysis

## Tools & Libraries
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Results
Refer to the notebook and output folders for model metrics and pricing simulation results.

## Submission
The presentation deck has also been submitted separately via the Google Drive link as required.
