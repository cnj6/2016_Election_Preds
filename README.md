# 2016_Election_Preds
Predict if counties vote Republican or Democrat based on given features.

- Created a Neural Network using Scikit-Learn’s Grid Search model selection to perform cross validation to produce a binary prediction (Democratic Party or Republican Party) on counties of the 2016 election given certain features which achieved 77.3% accuracy on an unknown dataset
-  Preprocessed data in CSV form by normalizing features and accounting for missing values
-  In addition to given features, created features for the change in birth and death rates between 2012 and 2016, as well as a KNN featured that used data regarding neighboring counties to map each county to a list of its neighbors’ IDs, and used those IDs to identify how neighboring counties voted
-  Worked closely with two partners in a Jupyter Notebook in Google Collaboratory

Viewing Project
- To see the code we wrote to analyze the dataset, view the CS 4780 Final Project ipynb file.
- The train_2016.csv and train_2012.csv files were used to train the models. They included election data from 1555 counties.
- The graph.cvs file was used to find any neighboring counties. We then made the neighboring counties its own feature and incorporated that into the models.
- The test_2012_no_label.csv files was our known testing dataset. This contains 1555 counties description data as well as the way they voted.
- After using these resources, our model was tested on a completely unknown dataset in Kaggle, on which it acheived 77.3% accuracy.
