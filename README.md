# World_Happiness_Visualization

**Life_ladder_by_country**
https://worldhappiness.report/ed/2021/#appendices-and-data
![Life_ladder](https://user-images.githubusercontent.com/85839235/140621693-465df65b-a2e8-49fe-907c-1e273fd1a5e6.png)

## Project Overview
Perform statistical analysis with the Life Ladder metrics that meaure perceived satisfaction and quality of life between the years 2008-2020.

## Overview of folder setup:

`Data` : consists of all the data used. Data has been sorted by years, and also converted to .csv files for each year. This is done using python code.

`Happiness`: contains the files needed to deploy local website for this project.

`app.py` is used for the userinput interactions 

`data.js` is the dataset converted to JSON file in order to be used.

`app.js` is used to build the datatable in the html page. It is also used for the filtering function in the website.

Any images used and CSS are in the subfolders in Happiness folder

`Machine_Learning`: correlation, hierarchical clustering, multi linear regression models files are in this folder. 

`static` subfolder contains images and plots for latest analysis

## Methodology
#### Life Ladder ####
  - Using the Life Ladder dataset, use the most recent year data for each country in order to perform statistical analysis. Visualize each country perceived life satisfaction score using Tableau. 
  - Using the Life Ladder dataset, use the most recent year data for each country in order to perform a Multi-Linear Regression Supervised Machine Learning and train a model with some of the data with the goal of finding an equation that would predict life satisfaction. **If a reliable equation for Life Satisfaction is achieved, build a visualizations regarding what each country biggest opportunity could be in order to improve the life satisfaction of their citizens would be (based on feature importance).**
  - Using the Life Ladder dataset, use the most recent year data for each country and train a Random Forrest Classifier in order to identify which variables seem to have the most impact in the decisions for life satisfaction of those interviewed. Compared each features impact on the Life Ladder variable. 

## Visualizations
  - Plot each country most recent Life Ladder data and color code it by their Life Ladder Score. 
  - Use Tableau for visualizations found from statistical analysis. 
  - Create a website to showcase results using previous website code as leverage. 
  - Also on this site allow for user to add their own inputs in order for the algorithm to predict a Life Ladder score based off those inputs. 
=======
