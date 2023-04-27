# online-shoppers-purchasing-intention

Classification - Online Shoppers Purchasing Intention
The purpose of this project is to analyze the purchasing behavior patterns of e-commerce visitors and to increase the conversion rate to purchase. The results show that page values has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 31.7% by applying model and actionable recommendation from insights.

Tools: Python, JupyterLab, Git

Libraries: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn

Dataset: Online Shoppers Purchasing Intention, UCI Machine Learning, 2018 [[source]](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

Summary of the analysis

- This dataset has 12330 observations and 18 variables with 10 numerical variables, 7 categorical variables and one target variable.
- All numerical variables have a right-skewed distribution and contain a lot of outliers.
- Revenue is the target variable that labels a visitor's purchase decision either purchase (class True) or not purchase (class False). The current condition is only 15% of total visitors who make a purchase.
- From exploratory data analysis, visitors with low exit and bounce rates and high page values, tend to make a purchase.
- Based on data characteristics, the selected algorithm to build a classification model is Gradient Boosting Classifier.
- The result shows that page values are the biggest impact on visitors' purchase decisions. The conversion rate to purchase increases up to 31.7% by applying model and  actionable recommendation from insights.

What I have learned

- Framing the business problem.
- Create a machine learning model and extract insight from it to make an actionable recommendation for the business team.
- Make a business simulation from insights that calculate the increase in the conversion rate.

File Dictionaries

- Final_ecTeam.ipynb: this notebook contains all of project details, such as business understanding, exploratory data analysis & insights, data preprocessing and modeling.
- Final Project Preparation Slide ec-Team.pdf: summary of the project.
- requirements.txt: list of used libraries with its version.
