# Titanic - ML From Disaster

Achieved accuracy of 81.56% and ranked in top 8% entries to predict the survival of a passenger.

Exploratory Data Analysis (EDA): I started by exploring the data to understand its structure, the types of variables I have, and the relationships between different variables. This is a crucial step in any machine learning project as it helps me understand the data I'm working with and informs my feature engineering and modeling strategies.

Data Visualization: I used various data visualization techniques to further understand the data and the relationships between variables. This is another important step in EDA as visualizations can often reveal patterns and insights that are not immediately apparent from looking at the raw data.

Feature Engineering: I created new features from the existing ones, such as 'Title' from 'Name' and 'FamilySize' from 'SibSp' and 'Parch'. Feature engineering is a key part of machine learning as the right features can significantly improve model performance.

Handling Categorical Variables: I used one-hot encoding to convert categorical variables into a format that can be used by the machine learning model. This is an important step as many machine learning algorithms cannot work with categorical data directly.

Handling Missing Values: I handled missing values in the data by filling them with appropriate values. In this case, I used the median of the respective columns. Handling missing values is important as they can cause errors with some machine learning algorithms.

Model Selection and Training: I used the RandomForestClassifier, a popular and powerful machine learning model for classification tasks. I trained the model on the training data and made predictions on the test data.

Model Evaluation: I evaluated the model's performance using accuracy, which is the percentage of passengers I correctly predict. This is known as accuracy.

Submission Preparation: I prepared a submission file with the required format for the Kaggle competition. This involved selecting the 'PassengerId' and 'Survived' columns from the test data and writing it to a CSV file.
