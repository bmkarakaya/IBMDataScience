# 🚀 SpaceX Capstone 🚀

This Capstone is the final course in the IBM Data Science Professional Certificate specialization, serving as a comprehensive project that summarizes all the materials learned throughout the program.
## Background
SpaceX stands as the most successful company in the commercial space age, revolutionizing space travel affordability. The project revolves around predicting whether SpaceX will reuse the first stage, a key factor in determining launch costs. With a focus on variables like payload mass, launch site, number of flights, and orbits, the goal is to understand their impact on the success of the first stage landing.
## Questions to be Answered:
* How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
* Does the rate of successful landings increase over the years?
* What is the best algorithm for binary classification in this case?

## Methodology
* Data collection methodology:
  * [SpaceX API](https://github.com/bmkarakaya/IBMDataScience/blob/main/1-%20jupyter-labs-spacex-data-collection-api.ipynb)
  * [Web scraping](https://github.com/bmkarakaya/IBMDataScience/blob/main/2-%20jupyter-labs-webscraping.ipynb)
* [Perform data wrangling](https://github.com/bmkarakaya/IBMDataScience/blob/main/3-%20labs-jupyter-spacex-Data%20wrangling.ipynb)
  * Filtering, dealing with missin values  
  * One-hot encoding
* Perform exploratory data analysis (EDA) using [visualization](https://github.com/bmkarakaya/IBMDataScience/blob/main/5-%20jupyter-labs-eda-dataviz.ipynb.jupyterlite.ipynb) and [SQL](https://github.com/bmkarakaya/IBMDataScience/blob/main/4-%20jupyter-labs-eda-sql-coursera_sqllite.ipynb)
* [Perform interactive visual analytics using Folium and Plotly Dash](https://github.com/bmkarakaya/IBMDataScience/blob/main/7-%20Build_an_Interactive_Dashboard_with_Ploty_Dash%20(1).ipynb)
* [Perform predictive analysis using classification models](https://github.com/bmkarakaya/IBMDataScience/blob/main/8-%20SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite%20(1).ipynb)
  * Logistic Regression, SVM, Decision Tree, K-nearest neighbors(KNN)
 
## Result

In this project, our goal is to predict whether the first stage of a given Falcon 9 launch will successfully land, a crucial factor in determining launch costs. Various features, including payload mass and orbit type, may influence the mission outcome. To achieve this prediction, several machine learning algorithms are applied, leveraging the patterns learned from past Falcon 9 launch data to create predictive models. Out of the four machine learning algorithms employed, the decision tree algorithm yielded the best performance in generating accurate predictions.
