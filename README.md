# Premier_League
Prediction of number of goals (&lt;2.5 or >2.5) for England Premier League, based on data from previous 11 seasons

### Data
Raw data are downloaded from https://www.football-data.co.uk/englandm.php
Explanation of columns names: https://www.football-data.co.uk/notes.txt
Merging of all seasons into one dataset, and cleaning of that dataset is done in data_preparation file

### data_preparation
Done in Jupyter Notebook with following versions od libraries:
pandas 1.1.3
numpy 1.19.2

Every line of code is commented

### Number_of_goals
Done in Jupyter Notebook with following versions od libraries:
pandas 1.1.3
numpy 1.19.2
scikit 0.23.2

Preprocessing of data, and training of several different models from sklearn library, with comparison of their results and fine tuning for chosen model
Prediction is done with data from new_round file.

### Results
Achieved accuracy on test dataset was around 55%, which was confirmed in reality (new_round data) with correct 6 results from 10 games.
Be free to work on this project and find a way to improve accuracy.
