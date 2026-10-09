# Credit Risk Prediction

A beginner-friendly data analysis and machine learning project that predicts whether a loan applicant is a good or bad credit risk.

## Dataset
German Credit dataset (1,000 loan applicants), loaded from OpenML.

## Tools
Python, pandas, matplotlib, scikit-learn, Google Colab

## What I did
1. Loaded and explored the data (no missing values, 70% good / 30% bad applicants)
2. Visualized bad-credit rates by credit history, age group and loan duration
3. Built two models: Logistic Regression and Random Forest
4. Compared them using accuracy, a classification report and confusion matrices
5. Identified the most important features

## Key results
- Logistic Regression accuracy: 75%. Random Forest accuracy: 75.5%.
- Logistic Regression caught about 80% of bad-credit applicants, while Random Forest caught only about 37%, so it is more useful for risk detection.
- Most important features: credit amount, loan duration and age.
- Bad-credit rates were higher for longer loans and for younger applicants.

## Limitations
Small and older dataset; not suitable for real loan decisions.

## Next steps
Try more models, tune parameters, and use a larger dataset.

## How to run
Open `credit_risk_project.ipynb` in Google Colab and click Runtime, then Run all.
