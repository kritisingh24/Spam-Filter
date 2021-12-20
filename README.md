## Spam-Filter

#### Dataset : https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

##### Abstract: 
The SMS Spam Collection is a public set of 5574 SMS labeled messages that have been collected for mobile phone spam research.

##### Data Set Information:
This corpus has been collected from free or free for research sources at the Internet:

-> A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages.

-> A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a dataset of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available. 

-> A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis.

-> Finally, have incorporated the SMS Spam Corpus v.0.1 Big. It has 1,002 SMS ham messages and 322 spam messages and it is public available.

##### Machine Learning Pipeline:
1. Read in raw text.
2. Pre-processing the dataset.
3. Feature engineering.
4. Fit simple model.
5. Tune hyperparameters and evaluate with GridSearchCV.
6. Final model selection.


##### Model evaluated:
-> Random Forest

-> Gradient Boosting

-> XGBoost
##### Metrics used:
-> Accuracy : #predicted correctly / total number of observations

-> Precision : # predicted as spam that are actually spam / total # predicted as spam

-> Recall : # predicted as spam that are actually spam / total # that are actually spam

##### Metrics used:
The best result is achieved by Random Forest Model with Precision: 0.964 / Recall: 0.865 / Accuracy: 0.977
