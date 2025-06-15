# Graduate-Admission-Prediction-using-Linear-Regression

This project analyzes graduate admission data and builds a Linear Regression model to predict an applicant's chance of admission to top universities. The dataset reflects key metrics such as GRE, TOEFL scores, CGPA, and more. This case study is framed around an educational platform offering admission assistance to students.

📌 Objective

To identify and understand key factors influencing graduate admissions and develop a predictive model to estimate the likelihood of admission using these features.

📊 Exploratory Data Analysis (EDA)

Dataset contains 500 records and 9 columns, including scores, ratings, and probabilities.

No null values or outliers found; the 'Serial No.' column was dropped as irrelevant.

CGPA, GRE, and TOEFL scores show strong correlation with admission chances.

Visual tools like histograms, scatter plots, pair plots, and boxplots were used to study distribution and relationships.

Linear trends observed between numerical features and the target variable (Chance of Admit).


🔍 Model Building and Evaluation

Built a Linear Regression model using both sklearn and statsmodels.

Checked assumptions of linearity, multicollinearity (VIF < 5), residual normality, and homoscedasticity.

Model Performance:

Train/Test MAE: 0.04

Train/Test RMSE: 0.06

R² Score: 0.82

Adjusted R²: 0.81

✅ Key Insights

CGPA, GRE, and TOEFL scores are the strongest predictors of admission probability.

Research experience, LOR, and SOP provide secondary contributions.

Strong LORs and SOPs still improve chances moderately, emphasizing the value of qualitative factors.

No signs of overfitting; residual plots confirmed good model generalization.

🎯 Recommendations

Institutions can offer guidance workshops to improve SOP and LOR quality.

Enhancing research exposure among students can incrementally increase their admission odds.

Continuous monitoring and model evaluation are advised to capture evolving admission patterns.

Introducing additional features like extracurriculars or internship experience can improve predictive power.
