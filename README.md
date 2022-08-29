# Credit_Risk_Analysis
UCD Module 17: Supervised Machine Learning and Credit Risk

The dataset titled "LoanStats_2019Q1.csv" was too large to upload. 

(The dataset is found in the zip file folder: [Module-17-Challenge-Resources.zip](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_17/Module-17-Challenge-Resources.zip).)

## Deliverables 1 (Use Resampling Models to Predict Credit Risk) and Deliverable 2 (Use the SMOTEENN algorithm to Predict Credit Risk):

(Deliverables 1 and 2 performed in [credit_risk_analysis.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb).)

## Deliverable 3 (Use Ensemble Classifiers to Predict Credit Risk):

(Deliverable 3 performed in [credit_risk_ensemble.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_ensemble.ipynb).)

## Deliverable 4 (Written Report on the Credit Risk Analysis):

The purpose of this assignment is to evaluate a credit card dataset (LoanStats_2019Q1.csv) in predicting credit risks. In the previous Module (Module 16), we found that Amazon reviews/results can be biased. In this Module (17), however, we apply different techniques to test the data as well as compoaring machine learning models. Doing so helps us reach an accurate-unbiased analysis, which is important when dealing with credit risk.

### Results of machine learning models:

- Oversampling (Naive) model in [credit_risk_analysis.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb): precision score was 0.01; recall was 0.63; F1 score was 0.02--conclusive that precision is low.

- Oversampling (Smote) model in [credit_risk_analysis.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb): precision score was 0.01; recall was 0.63; F1 score was 0.02--conclusive that precision is low.

- Undersampling model in [credit_risk_analysis.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb): precision score was 0.01; recall was 0.69; F1 score was 0.01--conclusive that precision is low.

- Combination sampling model in [credit_risk_analysis.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb): precision score was 0.01; recall was 0.69; F1 score was 0.1--conclusive that precision is low.

- Balanced Random Forest (Classifier) model in [credit_risk_ensemble.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_ensemble.ipynb): precision score was 0.03; recall was 0.70; F1 score was 0.06--conclusive that either a low precision score or recall results in a lower F1 score. 

- Easy Ensemble AdaBoost (Classifier) model in [credit_risk_ensemble.ipynb](https://github.com/michaelfoz/Credit_Risk_Analysis/blob/main/credit_risk_ensemble.ipynb): precision score was 0.9; recall was 0.92; F1 score was 0.16--conclusive that the F1 score is skewed by the low precision score.

### In conclusion, none of the machine learning models yielded sufficent results.
