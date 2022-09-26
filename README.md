# finding-donors ML project

#### This is the project for Udacity's Machine Learning nanodegree, in which i was tasked to find people most likely to donate to a charity organization given a dataset collected by the US census.

#### In the notebook, I start out by exploring the data to get a feel for the dataset. After that I initialize a naive base model that always outputs a true value and calculate it's accuracy for later comparison with the actual model. I then use multiple pre-processing techniques from one-hot encoding to data normalization to prepare the data for processing.

#### Three machine learning models were chosen, a GaussianNB classifier, a Decision Tree classifier and a Bagging classifier. The data was split into training and testing sets and the models were trained on the training set. Their performance was graphed and their accuracy/f-score/running time was compared to make a decision about the best model for the job. Of the three, the Bagging classifier was the superior model.

#### At the end, some experimentation was made to see if reducing the number of features affected the accuracy of the model greatly.
