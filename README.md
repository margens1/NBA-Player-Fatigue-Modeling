# NBA Schedule Analysis

This project analyzes NBA scheduling patterns and their potential impact on team performance. Using historical schedule and game data, the notebook identifies dense scheduling stretches (such as **4 games in 6 nights**), compares how often they occur across teams and seasons, and explores how factors like **back-to-backs, travel distance, and schedule density** affect outcomes.

## Objectives

- Count how often teams experience **4 games in 6 nights** scheduling stretches.
- Compare the **average number of dense scheduling stretches per team per season**.
- Identify teams with the **most and least demanding schedules** over the past decade.
- Evaluate whether scheduling differences across teams are **statistically significant**.
- Examine how performance changes when teams face **opponents on the second night of a back-to-back**.

## Data

The project uses the following datasets:

- **schedule.csv** – NBA game schedules by team and date  
- **team_game_data.csv** – Game-level performance statistics  
- **locations.csv** – Arena locations used to estimate travel distance  

## Methods

The analysis includes:

- Detecting **4 games in 6 days** scheduling windows  
- Normalizing counts to **per-82 games** for fair comparisons across seasons  
- Computing **league-wide team averages and z-scores**  
- Flagging **back-to-back games** for fatigue analysis  
- Estimating **travel distance** between games using geographic coordinates  
- Modeling schedule impact using **logistic regression**

## Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Plotly  
- Statsmodels  

## Running the Project

1. Install dependencies: pip install -r requirements.txt
2. Run Notebook Cells: schedule_project.ipynb






