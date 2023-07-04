# Kaggle Project : Students-drop-out-prediction
## Dataset Description
A dataset created from a higher education institution (acquired from several disjoint databases) related to students enrolled in different undergraduate degrees, such as agronomy, design, education, nursing, journalism, management, social service, and technologies.
The dataset includes information known at the time of student enrollment (academic path, demographics, and social-economic factors) and the students' academic performance at the end of the first and second semesters. The problem is formulated as a three category classification task (dropout, enrolled, and graduate) at the end of the normal duration of the course. The classes are coded as 0,1 and 2 in the dataset. All the original columns are anonymized for the competition purpose. However, the necessary information required for the model building is given below.

## Files
* train.csv - the training set
* test.csv - the test set
* sample_submission.csv - a sample submission file in the correct format

## Steps Followed
1. Dataset info & description
2. Train-test split
3. Data-Preprocessing
4. ML Model(Logistic Regression,SVC,KNeighbors Classifier,RandomForest Classifier with GridSearchCV)
5. Visualization & Confusion Matrix
6. Classification Report