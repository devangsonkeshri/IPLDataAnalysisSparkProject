# IPL Analysis Using PySpark on Databricks

This project contains various analyses of Indian Premier League (IPL) data using PySpark on the Databricks platform. The dataset includes ball-by-ball information, match-level data, player details, and team data.

## Project Files

- `IPL Data Analysis Using PySpark.ipynb`: The main notebook with all the code and analysis.
- `Ball_By_Ball.csv`: Detailed ball-by-ball data for IPL matches.
- `Match.csv`: Match-level data.
- `Player.csv`: Player information.
- `Player_match.csv`: Player performance data.
- `Team.csv`: Team details.

## How to Run This Project

To explore the analysis or run the code yourself, you can use [Databricks Community Edition](https://community.cloud.databricks.com/). Here’s how:

1. **Sign Up or Log In**: Create a free account or log in to Databricks Community Edition.
2. **Create a New Notebook**: Once logged in, create a new notebook in your workspace.
3. **Upload the Project Files**:
   - Import the notebook (`IPL Data Analysis Using PySpark.ipynb`) into your Databricks workspace.
   - Upload the CSV files to the Databricks file system (DBFS) or directly into the notebook.
4. **Run the Cells**: Open the notebook and run the cells to perform the analysis.

## Project Overview

The notebook covers the following analyses:
1. **Top Batsmen Identification**: Finding the top 5 batsmen in each IPL season.
2. **Team Performance**: Analyzing team wins, win margins, and the impact of toss results.
3. **Man of the Match Analysis**: Determine the players who have won the most "Man of the Match" awards in IPL history.
4. **Bowler Performance Analysis**: Find out which bowlers have taken the most wickets in each season.
5. **Toss Decision Impact**: Analyze whether winning the toss and choosing to bat or bowl first affects the outcome of the match.
6. **Venue-based Analysis**: Identify the venues where teams have the highest and lowest win rates.
7. **Calculate Years Since Debut**: Determine the total number of years since a player did Debut.
8. Impact of toss on Matches
9. Visualization of How a toss impact Individual Matches.
10. Visualization of Total runs scored on a venue.

## Requirements

- PySpark (Pre-installed on Databricks)
- Databricks Community Edition (Free platform for running the notebook)

## Note

The project is designed to be run on Databricks, so it includes PySpark-specific code and commands. If you'd like to run it locally, you'll need to install PySpark and adjust the code accordingly.

