Loan Approval Prediction
Overview
This project uses a decision tree classifier to predict whether a loan application will be approved based on applicant data, including income, credit history, and property area. The model was trained on a loan dataset, optimized for depth, and visualized to interpret decision rules.
Features

Data Preprocessing: Handled missing values and encoded categorical variables using LabelEncoder.
Exploratory Data Analysis: Analyzed feature distributions and their impact on loan approval.
Model Training: Trained a decision tree classifier with varying depths to find the optimal model.
Evaluation: Measured model performance with accuracy score.
Visualization: Visualized the decision tree using Matplotlib for interpretability.

Technologies Used

Python: Core programming language.
Pandas: For data manipulation and preprocessing.
Scikit-learn: For decision tree modeling.
Matplotlib: For visualizing the decision tree.

Installation

Clone the repository:git clone https://github.com/Aerglo/loan-approval-prediction.git


Install dependencies:pip install pandas scikit-learn matplotlib


Download the dataset (loan_data_set.csv) and place it in the data/ folder.
Run the Jupyter notebook:jupyter notebook loan_approval_prediction.ipynb



Usage

Open the loan_approval_prediction.ipynb notebook.
Execute cells to preprocess data, train the model, and visualize the decision tree.
Outputs include the decision tree plot and accuracy metrics.

Results

Achieved high accuracy with an optimized decision tree depth.
Identified credit history and applicant income as key factors in loan approval.

Future Improvements

Experiment with ensemble methods like Random Forest for improved performance.
Add feature importance analysis to highlight critical predictors.
Implement cross-validation for robust evaluation.

Contact
For questions or feedback, reach out to me at imnima82@gmail.com or via GitHub.
