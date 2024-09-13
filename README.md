# YouTube Adview Prediction
BY - ARPIT TYAGI

Machine Learning Project under Guidance of Internship Studio

<img src="https://user-images.githubusercontent.com/46225357/124817544-934fed80-df87-11eb-814f-2192f7df4b4c.jpeg" alt="alt text" height="500">

# Data Description

The file train.csv contains metrics and other details of about 15000 youtube
videos. The metrics include number of views, likes, dislikes, comments and
apart from that published date, duration and category are also included.

The train.csv file also contains the metric number of adviews which is our
target variable for prediction.

# Context

Youtube advertisers pay content creators based on adviews and clicks for the
goods and services being marketed. They want to estimate the adview based
on other metrics like comments, likes etc. The problem statement is therefore
to train various regression models and choose the best one to predict the
number of adviews. The data needs to be refined and cleaned before feeding
in the algorithms for better results.

# Attribute Information

'vidid' : Unique Identification ID for each video

'adview' : The number of adviews for each video

'views' : The number of unique views for each video

'likes' : The number of likes for each video

'dislikes' : The number of likes for each video

'comment' : The number of unique comments for each video

'published' : The data of uploading the video

'duration' : The duration of the video (in min. and seconds)

'category' : Category niche of each of the video

# Objective

To build a machine learning regression to predict youtube adview count based
on other youtube metrics.

# Steps and Tasks  

Import the datasets and libraries, check shape and datatype.
Visualise the dataset using plotting using heatmaps and plots. You can study data distributions for each attribute as well.
Clean the dataset by removing missing values and other things.
Transform attributes into numerical values and other necessary transformations.
Normalise your data and split the data into training, validation and test set in the appropriate ratio.
Use linear regression, Support Vector Regressor for training and get errors.
Use Decision Tree Regressor and Random Forest Regressors.
Build an artificial neural network and train it with different layers and hyperparameters. Experiment a little. Use keras.
Pick the best model based on error as well as generalisation. From my experiments, the best model is Support Vector Regression as its error is the least error among all.
Save the model and predicted on the test set.