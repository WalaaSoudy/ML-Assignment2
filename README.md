# ML-Assignment2

Problem 1: Decision Trees using Scikit-learn

Objective:
Build a model predicting the appropriate medication/drug type for patients based on Age, Sex, Blood Pressure, and Cholesterol levels.

1. Data Preprocessing:
Handle missing data and encode categorical variables. Count missing values, and address empty cells creatively.

2. First Experiment: Fixed Train-Test Split Ratio (30%):

Divide the dataset into training and testing sets (30%).
Repeat five times with different random splits.
Report sizes and accuracies of decision trees in each experiment.
Compare results and select the model with the highest overall performance.
3. Second Experiment: Range of Train-Test Split Ratios (30% to 70%):

Explore training set sizes from 30% to 70% in increments of 10%.
For each size, run the experiment with five different random seeds.
Calculate mean, maximum, and minimum accuracy, as well as mean, maximum, and minimum tree size.
Store statistics in a report.
Create two plots: one showing accuracy against training set size and another showing the number of nodes in the final tree against training set size.
Problem 2: KNN Implementation

Objective:
Implement a simple KNN classifier on the diabetes dataset without using built-in functions.

1. Data Preprocessing:

Divide data into 70% for training and 30% for testing.
Normalize each feature column separately using Log Transformation or Min-Max Scaling.
2. KNN Implementation:

Perform multiple iterations for different k values (e.g., 2, 3, 4).
Use Euclidean distance for computing distances between instances.
3. Break Ties using Distance-Weighted Voting:

In case of ties, consider distances between the test instance and tied classes' neighbors.
Assign higher weights to closer neighbors to break the tie, reflecting stronger influence from closer neighbors.
4. Output:

For each iteration, output k value and summary information (correctly classified instances, total instances, accuracy).
At the end, output the average accuracy across all iterations.
