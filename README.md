# Multiple-Disease-Prediction-using-Machine-Learning
A module that use machine learning and algorithms to identify the ultimate disease based on symptoms
The main actions you outlined are summed up as follows:
1. Collection Information: making use of a Kaggle dataset that consists of two CSV files: a training file and a testing file. There are 133 columns in the dataset; the last column indicates the prognosis, while the remaining 132 columns represent symptoms.
2. Data Cleaning: To guarantee that the machine learning model is of high quality, preprocessing the data is essential. The data is ready for training because every column is numerical, with the exception of the goal column (prognosis), which is encoded using a label encoder.
3. Model Building: Data may be utilized to train a machine learning model once it has been collected and cleaned. The Support Vector Classifier, Naive Bayes Classifier, and Random Forest Classifier will all be trained on this cleaned data. A confusion matrix will be used to assess the models' quality.
4. Conclusion: By combining the predictions of all three models, we will be able to forecast the disease based on the input symptoms after the three models have been trained. As a result, our prediction is more reliable and accurate overall.
