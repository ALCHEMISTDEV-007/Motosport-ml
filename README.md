# Motosport-ml
My Machine Learning journey with motorsport projects 🚀🏎️.
# Project 1: Motorsport Lap Time Analysis 🏎️📊

**Goal:** Explore lap times across drivers, tracks, and weather using Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset
- File: `datasets/motorsport_laptimes.csv`
- Rows: ~40
- Columns: `Driver, Team, Track, LapTime, Weather, PitStops`

## How to Run
Open the notebook in Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/motorsport-ml/blob/main/notebooks/project1_laptime_analysis.ipynb)

## Key Questions Answered
- Fastest lap overall and who set it
- Average lap time per driver
- Which tracks are generally faster/slower
- How weather affects lap time distribution

## Results (replace with your findings)
- **Fastest lap:** `XX.XXs` by `DRIVER` at `TRACK`
- **Fastest average driver:** `DRIVER`
- **Track with slowest average:** `TRACK`
- **Weather impact:** `e.g., Rainy shows higher median and more variance`

## Plots
- Bar: Average lap time per driver
- Box: Lap time distribution by weather
- Line: Average lap time per track

## Skills Used
- **Pandas & NumPy** for data wrangling
- **Matplotlib & Seaborn** for visualization

## Next Steps
- Add more laps and races
- Feature engineer stint length, tire type
- Try a regression model to predict lap times
