# Hybird-Email-Spam-classifcation
Emails are classified as either spam or not using ML algorithms and Deep learning

ML models take the word count of different words as input and based on the count of each words predict whehter the e-mail is spam or not.
Deep learning model uses RNN where the model is trained on which sequence of words can represent spam and which sequence can be not spam.

ML model used is Logistic regression and RNN model used is LSTM

First the email contents are extracted where the word counts for specific words which were used to train the ML model is found. This consists of words which occur most commonly in emails. This is then checked with the ML model. If the ML model predicts the given email as spam then execution ends or else the email contents are passed to the LSTM model. This then further checks the email to verify whether the email is spam or not. This two layer verfication ensures spam emails are never misclassified as HAM.
