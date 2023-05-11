# text-analysis
final assignment in the course Machine Learning. In this assignment I was asked to predict the story teller's gender whether is a male or a female, according to the store they wrote.

I went through cleaning the text, Including Stemming with prefixes and suffixes removal so I'll have better results with a clean text 
Then used the CountVectorizer to transform the to feature vector.

Then I used 9 different models, and put for every each individual model its parameters. that later on I found with  the hyperparamters fit for the features , and I checked for each one using GridSearchCV.

Finally I used evaluation to get the f1_score by macro, I used the model that gave me the best average F1 score and
I implemented the results to df_predicted to get the predictions on to the df_test which one is male and which one is female.
