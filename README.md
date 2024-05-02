# Ybi-Foundation_DS-ML_Internship

Data Preprocessing:

In the data preprocessing part, we first check for missing values and duplicate rows in the dataset. This helps ensure the data quality before proceeding with modeling. Missing values can be problematic for machine learning algorithms, and duplicate rows can skew the model's training process.

Data Visualization:

For data visualization, we present two visualizations. The first one is a count plot showing the distribution of wine quality ratings in the dataset. This gives us an understanding of how the quality values are distributed across different categories. The second visualization is a correlation heatmap, which shows the correlation between different features in the dataset. This helps us identify potential relationships between variables and can guide feature selection for the model.

Train Test Split:

Before training the model, we split the dataset into training and testing sets using the train_test_split function from the sklearn.model_selection module. This ensures that we have separate datasets for training and evaluating the model's performance.

Modeling:

For modeling, we use Support Vector Machine (SVM) from the sklearn.svm module. SVM is a powerful algorithm for classification tasks, and it works by finding the hyperplane that best separates the classes in the feature space.

Model Evaluation:

To evaluate the model's performance, we use confusion matrix and classification report metrics. The confusion matrix provides a summary of the model's predictions compared to the actual labels in the test set. It shows the number of true positives, true negatives, false positives, and false negatives. The classification report provides metrics such as precision, recall, and F1-score for each class in the dataset. These metrics give us insights into the model's accuracy and how well it performs for each class.

Prediction:

Once the model is trained, we use it to make predictions on the test set. We use the predict method of the SVM model to generate predictions for the test set features. These predictions can then be compared to the actual labels to evaluate the model's performance.
