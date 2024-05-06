# deep-learning-challenge

* Overview
For this analysis, we wanted to identify venutures with the highest chance of success. Because of the vollume of applicants and information we are looking to extract, training a machine learning model is our desired approach.

* Data Preprocessing
The ID columns,'EIN' and 'NAME', are not useful to us so we will drop both of them from our DataFrame. The target for our model will be the collumn 'IS_SUCCESSFUL'.

* Compiling, Training, and Evaluating the Model
Initially our model consisted of 2 hidden layers with 5 nodes in the first layer and 2 nodes in the second. This was done in attempts to keep processing time low while stull providing thorough and reliable results. This model did not meet the desired accuracy score of 75%, falling short at 72.75%

In attempts to reach a higher accuracy a third hidden layer was added to our model. The nodes in our model were also increased to 50 on each hidden layer. This slightly increase our accuracy score to 72.92%, but we were still unable to reach the target accuracy of 75%.

* Summary
Our model is preforming relativly well, but I would not suggest use in any major applications until the accuracy of the model can be increased. 
