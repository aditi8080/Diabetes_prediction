# Diabetes Prediction Using Decision Tree

## Project Overview
This project uses a Machine Learning algorithm called **Decision Tree Classifier** to predict diabetes based on medical and health-related data. The model is developed using Python and Scikit-learn.

## Objectives
- To analyze the diabetes dataset.
- To preprocess data for machine learning.
- To train a Decision Tree classification model.
- To predict diabetes outcomes.
- To evaluate model performance using accuracy, classification report, and confusion matrix.
- To improve model performance using hyperparameter tuning.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
The project uses a dataset named `diabetes.csv`. The target column is `Outcome`, which represents the diabetes prediction class.

- `0` – No diabetes
- `1` – Diabetes

## Algorithm Used
**Decision Tree Classifier**

A Decision Tree is a supervised machine learning algorithm that makes predictions using a tree-like structure of decision rules.

## Project Workflow
1. Import the required libraries.
2. Load the diabetes dataset.
3. Explore and analyze the data.
4. Separate input features and target variable.
5. Split the dataset into training and testing sets.
6. Train the Decision Tree model.
7. Evaluate the model performance.
8. Perform hyperparameter tuning using GridSearchCV.
9. Save the trained model using Pickle.

## Model Evaluation
The model is evaluated using:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Run the Project
1. Install Python or Anaconda.
2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Keep `diabetes.csv` and the Jupyter Notebook in the same folder.
4. Open the notebook in Jupyter Notebook.
5. Run all cells sequentially to train and evaluate the model.

## Output
The trained model predicts whether the input data belongs to the diabetes or non-diabetes class. The notebook also saves the trained model and feature names as pickle files.

## Future Scope
- Develop a web application using Streamlit.
- Compare Decision Tree with other machine learning algorithms.
- Improve model evaluation and validation.
- Create an interactive interface for predictions.

## Conclusion
This project demonstrates how a Decision Tree Classifier can be used for diabetes prediction using machine learning. It covers dataset analysis, model training, evaluation, and hyperparameter tuning.
