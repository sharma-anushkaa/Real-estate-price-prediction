# Real-estate-price-prediction
Predicting prices for an imaginary Singapore based company called Dragon Real Estate

This project was originally done here: https://www.codewithharry.com/videos/ml-tutorials-in-hindi-20.

Objective: 
			The objective of this end-to-end project is to build an ML model to predict the prices of the Real Estate in Singapore.

Explanation: 

			we find the type of model to be used: supervised, unsupervised or reinforcement learning. Our ML model is a supervised learning model.

			Next, would it be a Classification or Linear Regression model? The goals of this project demand a Linear Regression Model.

			Finally, Is this a batch learning or Online Learning Model? Since we have pre-determined data, we would be choosing batch learning. If I was to work on spam detection 
			
			in emails, the data would be constantly getting renewed and there I would choose Online Learning.
			

I divide the dataset into training and testing data, train the data on three models, namely: Linear Regression, Decision Tree and Random Forest. The results for the same are shown below.
I hae also used pipelines to automate the workflow, and the joblib library to dump and load the data.
OUTPUT 
I obtain these outputs:

Model Outputs

1. Decision Tree:
    Mean:  4.189504502474483
    Standard deviation:  0.848096620323756

2. Linear Regression:
    Mean:  4.221894675406022
    Standard deviation:  0.7520304927151625

3. Random Forest Regression
    Mean:  3.494650261111624
    Standard deviation:  0.762041223886678
	
Thus, we go forward with RandomForest, for maximum benifit of Dragon Real Estate Company
