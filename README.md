# Titanic Survival Prediction

This project is about predicting the survival of passengers on the Titanic. The dataset used in this project is the Titanic dataset from Kaggle.

## Project Structure

The project is structured as follows:

- Data Preprocessing: The data is preprocessed by handling missing values and scaling numerical features.
- Model Training: Several machine learning models are trained on the preprocessed data. These models include Random Forest, Decision Tree, Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Naive Bayes, and Neural Network.
- Model Evaluation: The models are evaluated based on their accuracy scores. A bar plot is used to visualize the accuracy scores of the different models.
- Prediction: The model with the highest accuracy score is used to make predictions on the test set.

## Requirements

- Python 3
- Libraries: pandas, numpy, matplotlib, scikit-learn

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the `Titanic.ipynb` notebook.

## Output

The output of the project is a CSV file named `submission.csv` which contains the predicted survival of the passengers in the test set. The CSV file has two columns: `PassengerId` and `Survived`.

## Final Score

The final score for this project, as evaluated by Kaggle, is 0.77751. And my final position at the time of making the repo was 4123.

## Note

This project is for educational purposes only. The accuracy of the predictions is not guaranteed.
