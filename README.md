# Slippi Replay Analyzer

A Python tool for analyzing Super Smash Bros. Melee game data. This tool generates statistics, visualizes key metrics, and creates network-based graph visualizations. Originally designed for the 100 Wins Challenge, it can be adapted for other replay datasets.

---

## Features

- **Data Analysis**:
  - Processes Slippi replays to generate detailed game statistics.
  - Summarizes win/loss data, stage preferences, and character usage.

- **Chart and Graph Visualizations**:
  - Generates bar charts and plots for detailed analysis.
  - Creates network visualizations for advanced relationship analysis.

- **Customizable**:
  - Easy to adapt to different datasets or metrics.

---

## Example Network: Moky's 100 Wins Challenge

The following network graph showcases the relationship between player damage ratio (damage given/taken) and ranks across Moky's games:

![Damage Ratio by Rank](output/Moky100WinsExample/graph_Moky100Wins_DamageRatio_sml.png)
*Graph created using Gephi.*

---

## General Stats

### Character Distribution
Shows the frequency of each character used across all games:
![Character Distribution](output/Moky100WinsExample/char_freq_all.png)

### Losses by Stage
Illustrates the most common stages where losses occurred:
![Losses By Stage with Most Common Character](output/Moky100WinsExample/stage_freq_all.png)

---

## Challenge Stats

### Losses By Day
Tracks stage losses across each day of the challenge:
![Losses By Day](output/Moky100WinsExample/loss_stage_day.png)

### Win Rate by Day
Visualizes the daily win rate throughout the challenge:
![Win Rate by Day](output/Moky100WinsExample/win_rate.png)

### Attempts
A simple plot of total attempts:
![Attempts](output/Moky100WinsExample/plot_no_stages.png)

### Losses By Character & Day
Breaks down losses by character and day:
![Losses By Character & Day](output/Moky100WinsExample/char_loss.png)

---

## Setup

### Requirements

- **Python**: Version 3.6+
- **Dependencies**:
  - `matplotlib`
  - `seaborn`
  - `Pillow`
  - `pandas`
  - `py-slippi==1.6.2`

Install the required libraries:
```bash
pip install matplotlib seaborn pillow pandas py-slippi==1.6.2
