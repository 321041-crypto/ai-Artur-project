# ai-Artur-project
##ai-Artur-project

##Problem

Many students do not clearly understand how study time and sleep impact academic performance. I built this project to predict a student’s test score based on hours studied and hours slept. This matters because it shows how data can be used to make decisions based on evidence rather than assumptions.

##Solution

The project uses a linear regression model to learn the relationship between study hours, sleep hours, and test scores. After loading the dataset, the model is trained to identify the best linear pattern connecting these variables. Once trained, it can take new inputs, such as 6 hours of studying and 8 hours of sleep, and output a predicted test score based on the learned relationship.

##Tools

The project was developed in Python using pandas to load and manage the dataset and scikit-learn’s LinearRegression model to train the predictive model. The dataset consisted of structured numerical values for hours studied, hours slept, and corresponding test scores.

##Results

The model detected a positive trend between both study time and sleep with higher test scores. When tested with new inputs, it produced predictions that followed the pattern shown in the data. This confirmed that the model successfully captured the linear relationship within the dataset.

##Learning

I learned that machine learning models depend heavily on the quality and size of the data provided. While the model worked well on a small dataset, it would require more data and proper evaluation methods to ensure reliable performance in real-world scenarios.
