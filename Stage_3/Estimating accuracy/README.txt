Candidate set contains 770 tuples.
Results for precision recall obtained:
((1.0, 1.0), (0.9722216822159181, 0.9869619912534696))

Recall = [1.0 - 1.0]

Precision = [0.972 - 0.987]

The following were our tables:
Table A - IMDB.csv (3250 tuples)
Table B - Metacritic.csv (3100 tuples)
Cadidate Set - Job_Movie_apply_rules_ds.csv
Prediction Set - apply_classifier_1.csv

Original size of candidate list - 770

Reduced Candidate Set (400 tuples) - reduced_Job_Movie_apply_rules_ds.csv
Labeled Set (400 tuples) - labeled.csv

PDF File detailing the number of candidate set tuples, density computation as well as the precision recall details - Precision_Recall.pdf

density_check.ipynb - Density calculation on the 50 tuples of the candidate set 
label_help.ipynb - Script to help label the 400 candidate set tuples

estimating_precision_recall.ipynb - Jupyter notebook provided with the file paths of the tables A, B, prediction list, candidate set, and the labeled csv files.
