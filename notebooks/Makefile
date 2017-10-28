########### pipeline for generating and evaluating a leaderboard submission ##########
leaderboard:
	# First generate the leaderboard datasets LB1, LB2 and LB4 and the submission skeleton
	python3 makeLeaderboardDataset.py --inputFolder ../data --outputFolder ../data

	# Then generate a simple forecast from the training data, and save it as TADPOLE_Submission_Pycon_TeamName1.csv ...
	# In TADPOLE_SimpleForecast1.py, you should replace TeamName1 with your team name and submission index,
	# e.g., TADPOLE_Submission_Leaderboard_TeamAwesome3.csv
	python3 TADPOLE_SimpleForecast1.py

	# Evaluate the user forecasts from TADPOLE_Submission_Leaderboard_TeamName1.csv against TADPOLE_LB4.csv using the evaluation function
	python3 evalOneSubmission.py --leaderboard --d4File ../data/TADPOLE_LB4.csv --forecastFile 	../data/TADPOLE_Submission_Pycon_TeamName1.csv

	# Submit (renamed version of) TADPOLE_Submission_Leaderboard_TeamName1.csv to TADPOLE website via the Submit page
