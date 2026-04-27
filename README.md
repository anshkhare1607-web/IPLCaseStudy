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



Task 5: Runs per Over
Objective
Compute average runs scored in each over (1 to 20).
Input
over
batsman_runs
Output
Array of size 20 representing average runs per over


Task 6: Boundary Analysis
Objective
Analyze boundaries in the dataset.
Tasks
Count total number of 4s
Count total number of 6s
Bonus
Identify which team has hit the most boundaries



Task 7: Death Overs Analysis
Objective
Analyze performance in death overs (overs 16–20).

Tasks
Total runs scored in death overs
Team with highest runs in death overs



Task 8: Highest Scoring Match
Objective
Find the match with the highest total runs scored.
Output
(match_id, total_runs)


Task 9: Runs per Team per Match
Objective
Calculate total runs scored by each team in each match.
Hint
You may need to combine:
match_id
batting_team



Task 10: Match Winner Approximation
Objective
Determine the winning team for each match based on total runs.
Steps
Compute runs scored by both teams
Compare totals
Identify the winner
Output
(match_id, winner_team)


