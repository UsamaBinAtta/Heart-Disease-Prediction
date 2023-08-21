# Heart-Disease-Prediction
Project Heart Disease Prediction Using Logistic Regression

Heart Disease

Welcome to the "Heart Disease Prediction Using Logistic Regression" project repository! In this project, we aim to predict the presence or absence of heart disease in individuals using logistic regression, a common machine learning algorithm for binary classification tasks.

Table of Contents

Project Overview

Dataset

Requirements

Usage

Model Training

Evaluation

Results

Contributing

License

Project Overview
Cardiovascular diseases, including heart disease, are a leading cause of death worldwide. Early detection of heart disease can significantly improve patient outcomes. This project demonstrates the use of logistic regression to predict heart disease based on a set of medical and lifestyle features.

Dataset

The dataset used for this project is sourced from Kaggle, and it contains various attributes such as age, sex, cholesterol levels, blood pressure, and more. It is divided into a training set and a testing set, which are used for model training and evaluation, respectively.

Requirements

To run this project, you'll need:

Python 3.7+
Required packages listed in requirements.txt
You can install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/usamabinatta/heart-disease-prediction.git
cd heart-disease-prediction
Install the required packages as mentioned in the Requirements section.

Prepare your dataset:

Download the dataset from [source-link].
Place the dataset files in the data/ directory.
Run the prediction script:

bash
Copy code
python predict_heart_disease.py

Model Training

The logistic regression model is trained using the training dataset. You can find the details of the model architecture, training parameters, and preprocessing steps in the train_model.ipynb Jupyter Notebook.

Evaluation

The trained model is evaluated using the testing dataset. The evaluation metrics include accuracy, precision, recall, and F1-score. You can find the evaluation results in the evaluation_results.ipynb Jupyter Notebook.

Results
Our trained logistic regression model achieved an accuracy of 85.25% on the testing dataset. The detailed evaluation metrics are available in the evaluation_results.ipynb notebook.

Contributing
We welcome contributions to enhance the project! To contribute:

Fork this repository.

Create a new branch.
Make your changes and commit them: git commit -m "Add feature XYZ".
Push to the branch: git push origin feature/your-feature-name.
Submit a pull request detailing your changes.

License
This project is licensed under the MIT License.
