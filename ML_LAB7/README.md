# Lab 7: Naïve Bayes Classification

## Aim
To implement the Naïve Bayes classification algorithm using the Glass dataset.

## Objective
To understand and apply Gaussian Naïve Bayes for classification and evaluate its performance.

## Dataset
- Dataset: `glass.csv`
- Input Features: RI, Na, Mg, Al, Si, K, Ca, Ba, Fe
- Target Variable: `Type`

## Algorithm
Gaussian Naïve Bayes is a supervised machine learning algorithm based on Bayes’ theorem. It assumes that the input features follow a Gaussian distribution within each class.

## Procedure
1. Import the required Python libraries.
2. Load the Glass dataset using Pandas.
3. Encode the target labels using LabelEncoder.
4. Split the dataset into training and testing sets.
5. Train the Gaussian Naïve Bayes model.
6. Predict the class labels for the test data.
7. Evaluate the model using accuracy and other classification metrics.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Result
The Gaussian Naïve Bayes classifier was implemented on the Glass dataset. The model generated predictions, and its performance was evaluated using classification metrics.

## Conclusion
The experiment helped understand how the Naïve Bayes algorithm performs classification using probability and Bayes’ theorem.
