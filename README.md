# Liverpool FC – Premier League Performance Analysis (2025–2026)

An end-to-end football data analytics project exploring Liverpool FC's performance through statistical

# Liverpool FC – Premier League Performance Analysis (2025–2026)

An end-to-end football data analytics project exploring Liverpool FC's performance using Python, statistical analysis, data visualization, and machine learning.

## Project Overview

This project analyzes Liverpool FC's performance across the 2025–2026 Premier League dataset, covering team performance, attacking and defensive efficiency, performance declines, tactical patterns, player contributions, and match outcome prediction.

## Objectives

- Benchmark Liverpool against Premier League teams.
- Diagnose attacking and defensive performance.
- Identify periods of declining performance.
- Analyze home and away performance and match situations.
- Evaluate player contributions and recruitment considerations.
- Develop and evaluate preliminary match outcome prediction models.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
Liverpool_Performance_Analysis/
│
├── data/
├── notebooks/
│   └── 01_Premier_League_EDA.ipynb
├── reports/
│   └── Liverpool_Performance_Report.docx
├── visuals/
│   ├── 01_League_Performance.png
│   ├── 02_Attacking_Efficiency.png
│   ├── 03_Defensive_Performance.png
│   ├── 04_Rolling_Points.png
│   ├── 05_Home_Away_Performance.png
│   └── 06_Player_Contributions.png
├── requirements.txt
└── README.md
```

## Key Findings

- Liverpool finished fifth in the supplied dataset with 60 points.
- The team scored 63 goals and conceded 53.
- Home performance was stronger than away performance.
- Attacking efficiency and away defensive performance were identified as areas for further investigation.
- Two periods of declining results were identified.
- Hugo Ekitike, Mohamed Salah, and Dominik Szoboszlai were among the leading attacking contributors in the supplied player data.

## Machine Learning

Three approaches were compared:

| Model | Accuracy | Log Loss |
|---|---:|---:|
| Baseline | 47.37% | 1.0645 |
| Logistic Regression | 44.74% | 1.0813 |
| Random Forest | 40.79% | 1.0943 |

Neither machine learning model outperformed the baseline.

## Visualizations

The `visuals/` directory contains six selected charts covering league performance, attacking efficiency, defensive performance, rolling points, home and away performance, and player contributions.

## Limitations

- The analysis uses supplied datasets that have not been independently verified as official season statistics.
- Only one season of match data was used.
- Expected goals, possession, injuries, and individual defensive actions were unavailable.
- Predictive model evaluation was based on a test set of 76 matches.

## Future Improvements

- Expand the dataset to multiple seasons.
- Incorporate expected goals and shot-location data.
- Add player defensive statistics.
- Explore additional predictive features and models.
- Improve model validation using larger chronological test samples.

## Disclaimer

This is an independent educational and portfolio project. Findings reflect the supplied datasets and should not be interpreted as official Liverpool FC performance reports.

## Author

Football Data Analytics Portfolio Project


## Data Sources & Attribution

Player statistics were collected from FBref, a Sports Reference website.

Source: [FBref – Liverpool FC 2025–2026 Premier League Stats](https://fbref.com/en/squads/822bd0ba/2025-2026/c9/Liverpool-Stats-Premier-League)

Data is used for educational and portfolio purposes. All original data and statistics are attributed to their respective source.

Match results and statistics were obtained from Football-Data.co.uk:

https://www.football-data.co.uk/mmz4281/2526/E0.csv