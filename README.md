Task 0: Data Loading and Preprocessing
Objective
Load both CSV files using NumPy
Requirements
Use np.genfromtxt() with proper parameters
Handle:
Header rows
Missing values
Mixed data types (strings and numbers)
Extract relevant columns into separate NumPy arrays

Expected Output
Arrays such as:
match_ids
batting_team
batter
bowler
batsman_runs
over



Task 1: Total Runs per Match
Objective
Compute total runs scored in each match
Input
match_id
batsman_runs
Output Format
[(match_id, total_runs), ...]
Constraints
Do not use dictionaries for aggregation
Use NumPy masking and aggregation


Task 2: Top 5 Batters
Objective
Find top 5 batters based on total runs
Input
batter
batsman_runs
Requirements
Use np.unique to identify batters
Use np.argsort for ranking
Output Format
[(player_name, total_runs), ...]




Task 3: Strike Rate of Batters
Objective
Calculate strike rate for each batter.
Formula
Strike Rate = (Total Runs / Balls Faced) × 100
Input
batter
batsman_runs


Task 4: Economy Rate of Bowlers
Objective
Calculate economy rate for each bowler.
Formula
Economy = Runs Conceded / Overs Bowled
Note
Convert balls to overs (balls ÷ 6)

