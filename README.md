# Project Goal
Use classification model to distinguish tweets are reliable or not. In nowadays, tweets information spread very fast and sometimes it even faster than news. However, not like journalist posts a news need a supervisor’s agreement. when people post tweets, they don’t think too much, or check is it a reliable source or not. They just re-tweet what they saw even it is fake news.
Therefore, the fake news would propagate very fast and people will hard tell which is reliable news which is not.

# Methods
1.Build Logistic Regression and SVM to classify tweets and get preliminary accuracy rate.  
2.Use NLTK module to paraphrase and expand tweets amount.  
3.Check POS for each word and check synonyms exist or not. If there has synonyms words then build new sentences.  
4.Build new Logistic Regression and SVM models to check accuracy rate.

# Result
Our model's accuracy rate enhance a little after we paraphrase our tweets. However, both models' accuracy rate doesn't enhance big. The reason may because of paraphrasing sentences
features too similar with original sentences, so the training model can't get great improve on prediction. In the future, we may want to try another paraphrase method to enhance
accuracy rate. Try to paraphrase the sentence using different sturcture because our method get same sentence structure and only change the vocabulary. If we can change to different
sentence structure, it might get better result.
