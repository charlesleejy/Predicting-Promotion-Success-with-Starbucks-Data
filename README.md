# Predicting-Promotion-Success-with-Starbucks-Data

Link to Medium: https://charlesleejy.medium.com/starbucks-capstone-challenge-3c826dd523d2

# Installation 
- Python versions 3.*.
- Python libraries:
  - Pandas
  - Numpy
  - Matplotlib
  - Seaborn
  - Scikit learn

# Project Motivation
The objective is to try to find how Starbucks customers use the app, and how well is the current offers system. ML models are used to predict the best offer to a specific customers by using transaction, demographic and offer data.

# File Descriptions
1. data:
      - portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
      - profile.json - demographic data for each customer.
      - transcript.json - records for transactions, offers received, offers viewed, and offers completed.
   
2. Starbucks_Capstone_notebook.* : contains all the work.

# Results
In this project, transaction, demographic and offer data are used to determine demographic groups response to offer type and thereby predict the best offer to give to a particular customer. Firstly, I did exploratory data analysis by answering some of the key questions, and conducted data preprocessing like data inputation for missing values, and normalisation of numerical values. From the analysis, it is apparant that females are more responsive to promotion than males since they have more completed offers. BOGO and Discount offers are also more popular promotions among the Starbucks customers.

# Licensing, Author, Acknowledgements
Credits must be given to Udacity for the starter codes and Starbucks for provding the data used by this project.
