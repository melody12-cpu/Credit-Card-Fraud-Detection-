# Credit-Card-Fraud-Detection-

Credit card fraud is a major financial issue that affects millions of people and businesses each year. As the use of online shopping and digital payments continues to grow, detecting fraudulent transactions quickly has become increasingly important. My model provides a way to analyze large amounts of transaction data and identify suspicious activity efficiently.

The goal of this project was to build a machine learning model that could classify credit card transactions as either fraudulent or legitimate. A dataset containing historical transaction records was loaded into Google Colab, where the data was preprocessed by separating the features from the target variable, scaling numerical values, and splitting the data into training and testing sets.

A logistic regression model was then trained using the processed data, with class weighting applied to help address the imbalance between fraudulent and legitimate transactions. The model was evaluated using precision, recall, a confusion matrix, and an ROC curve, and it was also used to predict whether new transactions were likely to be fraudulent.

The results showed that the model achieved a high recall, meaning it successfully detected most fraudulent transactions. However, its precision was lower because many legitimate transactions were incorrectly classified as fraud, largely due to the limited number of fraud cases in the dataset. Overall, the project demonstrated how machine learning can be used for fraud detection while highlighting the importance of balanced data and continued model improvement.
