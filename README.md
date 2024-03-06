# Projects

## <u>Predictive Machine Learning Projects</u>

## Analysis and Prediction of Bank Customer Attrition
  
**_Task Description:_** The task for this project was to design a pipeline that conisted of preliminary analysis, selection of machine learning methods, training and test data splitting, metrics selection and evaluation. 

**_Goal:_** The goal was to help a business manager of a consumer credit card portfolio to understand why customers were closing thier accounts and to predict which customers were likely to close their account in the future so that the manager could impliment strategies to combat customer attrition.

**_Technologies:_** Python, scikit-learn, pandas, numpy, matplotlib.

**_Method:_** I designed a pipeline, an evaluation strategy and a set of experiments to determin the best parameters and machine learning algorithm based on the results of empirical evlautaions derived from the dataset.

**_Outcome:_** An academic style report for my Ai and Machine learning module during my MSc in Data Science, I recieved a high distinction (81%).

**_Improvements:_**

**_Link:_** [Bank Customer Churn](https://github.com/Micky48/Customer-Churn-Prediction)


<br>


## London Crime and the Influence of Socio-economic Factors 
  
**_ Task Description:_** hypotheses 

**_Goal:_** Create a data science project with at least 800 lines of code and a 15,000 word report on a project of your choosing or from the list of suggested projects by supervisors. I decidedto conduct my own project and intitally wanted to look at increasing diversity in the outdoors, however I was unable to use the data in the end so decided to look at crime rates in London based on socio-economic factors instead.

**_Technologies:_** Python, scikit-learn, pandas, numpy, matplotlib, seaborn and Tableau.

**_Method:_** Using open source data from the London Datastore I gathered Recorded Crime: Geographic Breakdown (csv) for 12 different crimes by London borough by mm/yyyy, The Land Area and Population Density, Ward and Borough (csv) for population density by London borough by mm/yyyy , The Employees Earning Below the London Living Wage (LLW) (xls) for % of people erning below the LLW by London borough by mm/yyyy, The Model Based Unemployment Estimates (xls) for uneployment rates by London borough by mm/yyyy, Earnings by Workplace, Borough (xls) for data on workplace based annual median earnings by London borough by mm/yyyy. 

These datasets were then checked, missing values were imputed or columns/rows dropped, duplicates were removed, column names were standardised, datasets were reshaped and merged by borough and date then aggregated by various combinations of borough, year, month etc for analysis. Feature engineering was conducted to gain crime rates by borough which took into consideration borough population size. Exploratory data analysis was conducted looking at descriptive statistics, visulisations including histograms, boxplots, heatmaps and scatterplots to observe distribution, outliers and correlations. Copies of the data were created with normalisation and without normalisation and with outliers included and with outliers (outliers appeared to be genuine high or low data crime rates) removed to observe the difference in model perfromances. Feature selection was used such as K Select best to observe which socio-economic factors were thought to be most important in predicting crime rates. 

Data was then turned into an array using numpy, data was then split into 80% training data and 20% test data. Predictive models such as Random Forest Regressor and Support Vector Regression were used to try to predict crime rate in London using the socio-economic factors (multiple linear regression was also oberved but not used as the assumptions were not met). Numerous model experimentations (hyperparameter tuning) and evaluations then took place on the training data using cross validation. The evaluation metrics used were MSE, MAE, RMSE, R2, MBD and a learning curve visualisation. The final models were then tested on the test data with the best performing model being the Random Forest Regressor on the data with outliers removed explaining 80.4% of variance in London crime rates. The hyperparameters were: n_estimators = 100, max_depth = 10, min_samples_leaf = 2, max_leaf_nodes = 10. Random Forest Regressors feature importance graph suggested that population density contributed the most to predicting Lodnon crime rate, followed by median income.

_Outcome:_ A 15,000 word academic journal article written in Latex for my MSc Data Science final project, I recieved a high distinction (76%).

**_Improvements:_** Due to time contraints I was only able to look at overall crime rates in London but to further improve this project I would look at the influence that soci-economic factors play on specific crimes in London and I would try to find more open source socio-economic factor data measuring things like inequality and average household income. I also think it would be interesting to observe the effects of weather on crime rates.

**_Link:_** [London Crime Analysis and Prediction](https://github.com/Micky48/Final_Project)

## <u>Tableau Projects</u>

## COVID-19 Vaccination and Death Rates
