# Credit Scoring for Everyday Borrowers
In order to determine whether regular borrowers are at risk of defaulting, I developed an AI-powered credit scoring model for this project.  To find important borrower characteristics and spot any bias in model projections, I examined real-world data using machine learning algorithms like logistic regression, decision trees, and gradient boosting.

I used my knowledge of data visualization, model evaluation, supervised learning, and fairness audits.  This project was created as a component of the AI4ALL Ignite initiative, where I investigated the ethical applications of AI to solve practical problems and advance inclusion, equity, and transparency.


## Problem Statement <!--- do not change this line -->

This research investigates how machine learning can raise regular borrowers' credit scores. It tackles the demand for risk forecasts that are more equitable and precise, particularly as artificial intelligence becomes more prevalent in financial choices. The initiative demonstrates how AI may facilitate more responsible and inclusive lending by assessing model performance and bias.

## Key Results <!--- do not change this line -->

1. 89.8% model accuracy using Gradient Boosting.

2. Key features identified: call duration, past campaign success, balance.

3. Borrowers categorized into Low, Medium, and High risk.

4. Bias detected against single borrowers in predictions.

5. Call duration flagged as a potentially unfair feature.

6. Fairness analysis conducted using approval rates and confusion matrices.


## Methodologies <!--- do not change this line -->

Machine Learning Under Supervision

 Algorithms: Gradient Boosting, Decision Trees, and Logistic Regression
 -used to categorize debtors according to their likelihood of defaulting.

 Preprocessing of Data
 -One-hot categorical variable encoding
 -Label cleaning and mapping (e.g., "yes" → 1)

 Assessment of the Model
-Metrics: F1 Score, Accuracy, Precision, and Recall
-Model performance is evaluated using the confusion matrix.

 Classification of Risk
-Borrowers are classified as Low, Medium, or High risk based on probability levels.

 Analysis of Fairness and Bias
-Comparison of approval rates by marital status group
-Evaluation of bias from features such as call duration

 Analysis of Feature Importance
-The best predictive borrower attributes are ranked via gradient boosting.

## Data Sources <!--- do not change this line -->

Kaggle dataset: https://www.kaggle.com/datasets/kapturovalexander/bank-credit-scoring

## Technologies Used <!--- do not change this line -->
The technologies, libraries, and frameworks used in our project.
- Google Colab
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Avneet Kaur  (kavneet194@gmail.com)*
- *Karsten Assoua (karsten@brown.edu)*
