# online-shoppers-purchasing-intention

Classification - Online Shoppers Purchasing Intention
The purpose of this project is to analyze the purchasing behavior patterns of e-commerce visitors and to increase the conversion rate to purchase. The results show that page values, the number of visited pages, has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost the number of visited pages.

Tools: Python, JupyterLab, Git

Libraries: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn

Dataset: Online Shoppers Purchasing Intention, UCI Machine Learning, 2018 [source]

Summary of the analysis

- This dataset has 12330 observations and 18 variables with 10 numerical variables, 7 categorical variables and one target variable.
- All numerical variables have a right-skewed distribution and contain a lot of outliers.
- Revenue is the target variable that labels a visitor's purchase decision either purchase (class True) or not purchase (class False). The current condition is only 15% of total visitors who make a purchase.
- From exploratory data analysis, visitors with low exit and bounce rates and high page values, tend to make a purchase.
- Based on data characteristics, the selected algorithm to build a classification model is tree-based or ensemble. The classification model with the random forest algorithm is able to correctly predict 62% of visitors who make a purchase.
- The result shows that page values, a number of visited pages, are the biggest impact on visitors' purchase decisions. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost page values of visitors.

What I have learned

- Framing the business problem.
- Create a machine learning model and extract insight from it to make an actionable recommendation for the business team.
- Make a business simulation from insights that calculate the increase in the conversion rate.

File Dictionaries

- Final_ecTeam.ipynb: this notebook contains all of project details, such as business understanding, exploratory data analysis & insights, data preprocessing and modeling.
- Final Project Preparation_ec-Team.pptx: summary of the project.
- requirements.txt: list of used libraries with its version.
