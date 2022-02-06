# Corona_Tweet
Knowing what the public thinks about corona-virus will help policy makers to decide on the strategies against the COVID pandemic. <br>
SpringboardProject3. Data from Kaggle.com 

## Folder1: Data
<ul>
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/Corona_NLP_train.csv" >Original_Train.csv</a></li> 41157 non-null ‘OriginalTweet’ and ‘Sentiment’ observations
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/Corona_NLP_test.csv" >Original_Test.csv</a></li> 3798 non-null ‘OriginalTweet’
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/ProcessedTweets" >Cleaned_Training_Data.csv</a></li> Tokenized and cleaned text
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/ProcessedTestData" >Cleaned_Test_Data.csv</a></li> Tokenized and cleaned text
</ul>

## Folder2: Notebooks
<ul>
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Notebooks/NLP_EDA_PreProcessing.ipynb" >
NLP_EDA_PreProcessing.ipynb </a></li> texts were cleaned, tokenized, and vectorized before fitting into several models 
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Notebooks/MultiDenselayer_3Classes_Tweet.ipynb" >
MultiDenselayer_3Classes_Tweet.ipynb </a></li> texts were preprocessed then fitting into a multilayer Neural Network model, used 3 classifiers with an accuracy of 0.82. Metrics included classification report and confusionn matrix
<li><a href="https://github.com/mengyanl/Corona_Tweet/tree/main/Notebooks/Other_Fitted_Models" > 
Other models used </a></li> Did SVC (linear kernel) and multilayer NN after vectorizing using CountVectorizer and Tfidf vectorizer, RandomForest and XGboost also tried. Accuracy slightly lower than  with an accuracy of 0.67. Metrics included classification report and confusionn matrix. NN had the best outcome.
</ul>

### Project Final Presentation: <a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Presentation_Tweet_interview.pptx" >Tweet_Sentiment_Analysis_Presentation  </a>
