Interpretable Machine Learning: SHAP Analysis of Credit Risk Prediction

This project develops a complete, interpretable Credit Risk Classification system using advanced machine learning techniques and Explainable AI (XAI). The focus is not only on building a high-performing predictive model but also on providing transparent, SHAP-based explanations for individual and global predictions an essential requirement in regulated financial environments.

The project follows the end-to-end ML pipeline, including preprocessing, model training, evaluation, and explainability.

Project Structure
credit-risk-shap-analysis/

README.md
Credit_Risk_Project.ipynb
 data/
credit_risk_dataset.csv

models/
random_forest_model.pkl
logistic_regression_model.pkl
preprocessor.pkl
figures/
shap_summary.png
feature_importance.png
correlation_heatmap.png
shap_outputs/
shap_values.npy
base_value.txt
credit_output.zip-Contains all exported results

Objective

To predict whether a borrower will default on a loan using:

Random Forest Classifier (Primary Model)

Logistic Regression (Baseline Model)

SHAP Explainability (Global + Local Interpretability)

The model explains which financial or demographic factors contribute most to the prediction—critical for transparent credit scoring.

Technologies & Libraries Used

Python 3.x

pandas, numpy

scikit-learn

matplotlib, seaborn

SHAP

joblib

How to Run the Project
1️ Install Dependencies
pip install pandas numpy scikit-learn shap joblib matplotlib seaborn

2️ Add the Dataset

Place the dataset inside the data/ folder:

data/
credit_risk_dataset.csv

3️ Run the Notebook
jupyter notebook


Open:

Credit_Risk_Project.ipynb

4️ (Optional)

Modify dataset/model paths inside the notebook if using custom directory structures.

 Outputs Generated
 Model Evaluation Metrics

Saved as: model_metrics.txt

Includes:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

Confusion Matrix

 Model Artifacts

Located under models/:

random_forest_model.pkl

logistic_regression_model.pkl

preprocessor.pkl

These files allow full reproducibility and deployment.

 Explainability (SHAP)

Stored under figures/ and shap_outputs/:

shap_summary.png – Global SHAP summary plot

shap_values.npy – Computed SHAP values

base_value.txt

Individual prediction explanations (local SHAP)

SHAP outputs help identify:

Top contributing features

How each feature influences prediction

Loan approval/denial explanations

Visualizations

Saved inside figures/:

Correlation Heatmap

Feature Importance Bar Plot

SHAP Summary Plot

Project Tasks Completed (As Required)

Preprocessed dataset & handled missing values
Trained RandomForest & Logistic Regression models
Calculated SHAP values for interpretability
Generated global + local explanations
Identified top 3 global influential features
Provided domain-driven reasoning useful for credit officers

All Project Outputs

All generated files are packaged in:

credit_output.zip


This includes models, SHAP outputs, figures, and metrics ready for submission or deployment.

Conclusion

This project delivers a complete, production ready and fully explainable Credit Risk Prediction Pipeline. The inclusion of SHAP ensures transparency and accountability, making it suitable for real-world financial decision making.
