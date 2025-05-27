# Curry vs Lillard Shot Analysis (2023-24 NBA Season)

This project is a comparative analysis of **Stephen Curry** and **Damian Lillard's** shot selection and shooting efficiency during the **2023-24 NBA season**. By using the `nba_api` package, I extracted detailed shot data for both players, created visualizations, and analyzed their shooting tendencies across different areas of the court.

## Project Overview

The objective of this project is to:
- Understand the shot distribution for Stephen Curry and Damian Lillard.
- Analyze shooting efficiency in different court zones (near the rim, mid-range, and three-point range).
- Provide insights into where each player is most and least effective on the court.

This analysis includes:
- Shot charts (made vs. missed shots).
- Heatmaps showing shot density.
- Shooting percentage comparison across different zones.

## Data Sources

The shot data for Stephen Curry and Damian Lillard is retrieved using the **nba_api** package. The data represents shot attempts during the **2023-24 NBA regular season**.

Files included:
- `curry_shot_data_2324.csv`: Contains shot data for Stephen Curry.
- `lillard_shot_data_2324.csv`: Contains shot data for Damian Lillard.


## Project Setup

To set up this project on your local machine, follow these steps: 

1. **Clone the repository**: Clone the repository from GitHub to your local machine using the follow command:

```bash
git clone https://github.com/Oscuh/Curry-vs-Lillard.git
```
2. **Navigate to the project directory**: After cloning to repository, move into the project directory:

```bash
cd Curry-vs-Lillard
```
3. **Installation**: Install the necessary Python packages by running the following command:

```bash
pip install nba_api pandas matplotlib seaborn
```
4. **Open Jupyter Notebook**: Launch Jupyter notebok to start analysis:

```bash
jupyter notebook CurryDamianAnalysis.ipynb
```

## Usage

Run the cells to:
  - Retrieve shot data for both Stephen Curry and Damian Lillard using the **nba_api**
  - Generate visualizations including shot charts and heatmaps
  - Compare shooting percentages from different court zones.

## Key Analysis Sections: 

- **Shot Location Mapping** – Visualize where each player takes shots from, categorized by makes and misses
- **Heatmaps** – Identify high-frequency shooting zones
- **Efficiency Breakdown** – Compare shooting percentages near the rim, mid-range, and beyond the arc
- **Observations** – Discuss patterns and insights regarding each player’s offensive tendencies

## Conclusion

This project provides a side-by-side comparison of Stephen Curry and Damian Lillard's shot selection and efficiency during the 2023–24 NBA season. By visualizing shot data and analyzing shooting performance across different zones, we gained insights into each player's offensive tendencies and scoring strengths. While both players are elite shooters, the analysis highlights their differences in court usage, preferred shooting spots, and overall efficiency. This framework can be extended to other players, seasons, or used for team-level strategic analysis.
