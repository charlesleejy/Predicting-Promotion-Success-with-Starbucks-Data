# Predicting-Promotion-Success-with-Starbucks-Data




Udacity Data Scientist Nanodegree
Starbucks Capstone Project
Table of Contents
Project Motivation
Installation
File Descriptions
Results
Licensing and Acknowledgements
Project Motivation
This project part of my Data Science Nanodegree,

Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.Not all users receive the same offer, and that is the challenge to solve in this project.
we will combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.
The problem statement I am aiming to answer are :
(1) Discover customer attributes as Age , income, gender.
(2) Discover How long did the users become members ? .
(3) predict whether or not the offer will respond by the person.
Using the data provided (portfolio, profile, Transactional),I answer first and second question using charts and i answer the third question using 6 classification models.
Installation
This project requires Python 3.x and Python libraries in requirements.txt

File Descriptions
Starbucks_Capstone_notebook.ipynb jupyter notebook
Starbucks_Capstone_notebook.html jupyter notebook HTML
requirements.txt necessary libraries
portfolio.json Offers sent during 30-day test period (10 offers x 6 fields)
profile.json Rewards program users (17000 users x 5 fields)
transcript.json Event log (306648 events x 4 fields)

Results
Actually, most metrics are great and I like to evaluate many metrics but from our business question and since we have a simple classification problem, Accuracy is a great metric to evaluate my models, because We want to see how well our model by seeing the number of correct predictions vs total number of predictions. and anwser the question : How many custemrs use Starbucks offers?.this is my opinion and reasoning on why to use the easiest metric (accuracy). Models results My analysis suggests that the resulting GaussianNB model has an bogo training data accuracy of 64 and bogo test accuracy of 62 . discount training accuracy of 0.929 and discount test accuracy of 60 suggests that the GaussianNB model I constructed did not overfit the training data.

The Blog Post can be found Here

Licensing and Acknowledgements
Credits must be given to Udacity for the starter codes and Starbucks for provding the data used by this project.
