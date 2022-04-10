# IBM-Data-Science-Repository
This repository highlight my data science projects completed as part of the IBM Data Science Professional Certificate. It contains Jupyter notebooks of the work that I've completed

## Machine Learning Project
In this project, I read a file containing the loan status of various people. The data set contained information about the person's gender, education, age, loan amount, loan status (Paid off or collected) and several other fields. 

I cleaned the data including converting text to integers and text to dates. Next, I visualized the data to better understand it. Lastly, I prepared the data to be used in the machine learning algorithm by selecting all necessary fields and normalizing the data. 

The goal of the project was to determine which classification alogorithm yeilded the best results so, this dataset was used to train 4 separate algorithms: K Nearest Neighbour, Decision Tree, Logistic Regression and Support Vector Machine. 

The training data was split into a training set and a testing set. I iterated each alogorithm to determine the optimal parameters that yeilded the highest accuracy.

After training the models, a testing data set was used to determine which model was the best classifer. The evaluation metrics used were: jaccard score, f1 score and LogLoss Score.

Feel free to read the jupyter notebook for more details.

## King's House Regression Project
In this project, I used financial data to predict the price of houses based on features such as square footage, number of bedrooms, number of bathrooms, etc. To begin, I loaded the data, which was hosted on IBM's servers. I ran an exploratory analysis by determining what data types were present in the dataset and converted them to more suitable data types as needed.

I detemined which features in the dataset had the highest correlation to price by plotting scatterplots, box plots and used the corr() function within Python's Pandas library. 

Once the features with the highest correlation to price were determined, I split the data into a training set and a testing set. i then performed a multi linear regression analysis using the training data set and tested the model with the testing set. I then evaluated the results of the regression using the R^2 score. I also performed a second order polynomial regression to determine whether a polynomial regression was more suitable for this dataset.

I introduced a regularization parameter to mitigate the risk of over fitting the polynomial regression. This model was also evaluated using the R^2 score and the results of both models were compared to determine which regression could better predict housing prices.

Feel free to read the Jupyter notebook for more details.
