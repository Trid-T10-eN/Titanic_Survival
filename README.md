This is my first ever proper code, with two machine learning models I used here. 
At first, I cleaned my dataset and pre-processed it, by removing the null values, or replacing them
Then, I fit the data into a Random Forest and Linear Regression model, to cross-check with the observations. 
In the end, I used visualizing tools like Seaborn and Matplotlib to visualize the data.


A few things that are needed to be noted:
one issue that I noticed was the 'Cabin' column sometimes vanished: there was a key error saying <<['Cabin'] not found in axis>>. The way i resolved this is by
continuously executing the top rows. Although I'm unsure why this issue kept appearing.

i actually used an OLS to try and check for correlations, and from the p-values I can understand that 'SibSp' holds a negative correlation to survival rate unlike the others
but when i tried to remove values, there was always an extra variable and I couldn't understand why. Googling it lead me to
<<It could be another feature from your dataset that was included in the regression, or it might be an interaction term or transformed variable.>>, which I wasn't able to decipher.
