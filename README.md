# heart_disease_prediction
A healthcare organization together with a couple of government hospitals in a city has collected information about the vitals that would reveal if the person might have a coronary heart disease in the next ten years or not. This study is useful in early identification of disease and have medical intervention if necessary. This would help not only in improving the health conditions but also the economy as it has been identified that health performance and economic performance are interlinked. Given the data, we need to develop appropriate models to identify/predict if the person likely to have heart disease or not. 

# Data Description
•	The total number of records is 34,281 with 24 independent attributes and the 25th column is the target which needs to be predicted.

•	The variables are masked, and we get little information from their names.

•	Missing values are represented as NA in some columns and as -99 in some other columns 


# Data Pre-processing 
•	How are you planning to work with missing values? First, different representations must be brought to same representation and then you may choose one of the imputation methods/ choose to eliminate the records. In either case justify your actions.

•	In the data some of the variables may not be relevant for analysis. How such variables can be identified, and this issue be resolved. There are functions that can identify such columns.

•	Since you are expected to build multiple models, justify why the selected model is suitable for the given problem and the method data pre-processing for the model

# Exploratory data analysis
•	This is where we would like to see, how well you have understood the data? Any insights from the data given at this stage might be helpful. 

•	Observe the ratio of positive to negative classes in the data (1 being positive and 0 is negative). Do you think the number of positive instances sufficient? Think.

# Statistical Hypothesis Testing 

•	Check whether the following variables impacts the target variable?

•	Write the NULL and Alternative hypothesis 

•	Apply suitable statistical test and comment on the output 
i.	 IV
ii.	 A2
iii.	A5
iv.	A8
v.	A191

# Model Building

•	What type of the problem is this? Classification or Regression? 
•	What is the most suitable error metric to measure the model performance?
•	Select and build at least 3 models and compare the model performance
i.	 Logistic Regression model
ii.	Step AIC Logistic Regression model
iii.	Lasso model
iv.	Ridge model 
v.	 Elastic net
vi.	Naïve Bayes
•	Draw the ROC curves and select the suitable threshold value
•	You can choose one model and identify the top 5 factors that are impacting the model performance
•	Explain how each variable impacts the model performance
•	What is your final recommended model? 
•	How do you think this model helps?
•	Remove the target variable and apply PCA 
•	How many components will you recommend and justify your choice with your visualization

