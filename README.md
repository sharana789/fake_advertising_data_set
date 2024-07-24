# fake_advertising_data_set
Logistic Regression Project

- **Data Import and Initial Exploration:**
  - Imported necessary libraries: pandas, numpy, matplotlib, seaborn.
  - Loaded the advertising dataset into a DataFrame and checked the head, info, and summary statistics.

- **Exploratory Data Analysis (EDA):**
  - Created histograms to visualize the distribution of the 'Age' feature.
  - Used seaborn jointplots to explore relationships between 'Age' and 'Area Income', 'Age' and 'Daily Time Spent on Site', and 'Daily Time Spent on Site' and 'Daily Internet Usage'.
  - Created a pairplot colored by the 'Clicked on Ad' feature to observe patterns and correlations.

- **Data Preparation and Model Training:**
  - Selected features ('Daily Time Spent on Site', 'Age', 'Area Income', 'Daily Internet Usage', 'Male') for the model.
  - Split the data into training and testing sets using `train_test_split` with a 33% test size and a random state for reproducibility.
  - Trained a logistic regression model on the training data using sklearn's `LogisticRegression`.

- **Model Evaluation:**
  - Predicted the test data using the trained model.
  - Evaluated model performance by generating a classification report, which included precision, recall, and F1-score metrics for the predictions.
