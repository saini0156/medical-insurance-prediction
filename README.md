# medical-insurance-prediction
Briefly explain that this model predicts insurance charges with high accuracy.

🚀 Performance Summary

The model achieved an exceptional fit on the test data:

Model Performance: Highlight your 97.5% $R^2$ score.

Mean Squared Error: Evaluated through residual analysis, showing high precision.

Error Analysis: Residuals are normally distributed and centered around zero, indicating Low Bias and Low Variance.

🛠️ Dataset and Features:

The model was trained on medical_insurance_10000.csv. The following features were preprocessed and encoded:
Numerical: age, bmi, children.

Categorical: sex (encoded 0/1), smoker (encoded 0/1), region (encoded 1-4).

Target Variable: charges
.
💻 Installation & Usage

1. Clone the Repository:git clone https://github.com/YourUsername/medical-insurance-prediction.git
cd medical-insurance-prediction

3. Install Dependencies :
   pip install -r requirements.txt
   
5. Run the Model
   You can view the full analysis and training steps by opening the Jupyter Notebook:
   jupyter notebook MEDICAL_INSURACE.ipynb
   
📈 Key Insights

1.Model Fit: The strong $R^2$ score suggests that the relationship between these specific features and insurance costs is highly linear.

2.Preprocessing: Manual label encoding was used to transform categorical data into a format suitable for Scikit-Learn's LinearRegression.

3.Bias-Variance Tradeoff: Since the performance remains high on the unseen test set (20% of data), the model is not suffering from significant overfitting.

👤 Author

NITISH SAINI
