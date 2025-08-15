Credit Risk Model for University Project
This repository documents a credit risk model developed as a university project. The objective was to build a robust predictive model that estimates the probability of a loan defaulting. The project is organized into three distinct phases, each captured in a separate Jupyter Notebook, to ensure a clear and reproducible workflow.

Dataset
The dataset used for this project, Loan_default.csv, was sourced from Kaggle. It contains a variety of features related to borrowers and their loan applications, which are used to predict the likelihood of default.

Kaggle URL: www.kaggle.com/datasets/nikhil1e9/loan-default

Project Structure
The project is structured around three key notebooks that cover the entire model development life cycle:

ProbabilityOfLoanDefaultEDA.ipynb

ProbabilityOfLoanDefault_ModelComparisonAndVisualisatiion.ipynb

ProbabilityOfLoanDefault_finalModel.ipynb

ProbabilityOfLoanDefaultEDA.ipynb
This notebook is dedicated to Exploratory Data Analysis (EDA). It provides a comprehensive investigation of the dataset to gain a deeper understanding of the features and their relationship with the target variable (loan default). The key steps included:

Initial data cleaning and preprocessing.

Univariate and bivariate analysis of key features.

Extensive use of visualizations to uncover trends and patterns.

Deriving insights that inform the subsequent modeling stages.

ProbabilityOfLoanDefault_ModelComparisonAndVisualisatiion.ipynb
In this phase, multiple machine learning models are compared to identify the most promising candidates. This notebook focuses on:

Training and evaluating various classification models.

Using Cross-validated AUC as the primary metric for fair model comparison.

Optimizing models through hyperparameter tuning.

Critically, this section explores model performance without using any data balancing techniques to establish a strong baseline.

ProbabilityOfLoanDefault_finalModel.ipynb
This final notebook details the process of building and selecting the ultimate credit risk model. It represents the culmination of all previous work and includes:

Advanced Feature Creation: Developing new, more predictive features from the existing dataset.

Final Model Comparison and Selection: A final round of model comparisons.

Strategic Model Selection: The final model was not selected based on a single metric. While a high Precision score was a primary goal to minimize false positives, a careful balance between Precision and Recall was considered to ensure the model is both accurate and effective at identifying true defaults.
