# Corona_Tweet
Knowing what the public thinks about corona-virus will help policy makers to decide on the strategies against the COVID pandemic. <br>
SpringboardProject3. Data from Kaggle.com 

## Folder1: Data
<ul>
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/Corona_NLP_train.csv" >Original_Train.csv</a></li> 41157 non-null ‘OriginalTweet’ and ‘Sentiment’ observations
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/Corona_NLP_test.csv" >Original_Test.csv</a></li> 3798 non-null ‘OriginalTweet’
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/ProcessedTweets.csv" >Cleaned_Training_Data.csv</a></li> Tokenized and cleaned text
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Data/ProcessedTestData.csv" >Cleaned_Test_Data.csv</a></li> Tokenized and cleaned text
</ul>

## Folder2: Notebooks
<ul>
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Notebooks/Tweet_NLP_EDA_PreProcessing.ipynb" >
Cleaning_EDA_Preprocessing.ipynb </a></li> texts were cleaned, tokenized, and vectorized before fitting into several models -- tried multiple decided using SVCClassifier
<li><a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Notebooks/Tweet_Final_SVC_Model_Metrics.ipynb" > 
Tweet_Final_SVC_Mode_Metrics.ipynb </a></li> Did GridSearchCV, finalized with a SVC (linear kernel) after vectorizing using CountVectorizer with an accuracy of 0.67. Metrics included classification report and confusionn matrix.
<li><a href="https://github.com/mengyanl/Corona_Tweet/tree/main/Notebooks/Other_Fitted_Models" >SVC_IFIDF_RF_XGBoost_Models</a></li> Also did hyperprameter tuning using GridSearchCV using SVC (rbf kernel) after Tfidf vectorizer, RandomForest and XGboost. Accuracy slightly lower than SVC after a CountVectorizer.
</ul>

### Project Final Presentation: <a href="https://github.com/mengyanl/Corona_Tweet/blob/main/Presentation_Tweet.pptx" >Tweet_Sentiment_Analysis_Presentation  </a>
