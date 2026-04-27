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
