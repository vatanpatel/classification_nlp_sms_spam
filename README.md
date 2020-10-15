# Welcome
This is my first notebook on NLP. I have chosen the Hello World dataset for NLP. The dataset is from kaggle and can be found [here](https://www.kaggle.com/vatanpatel/lendingclub). The orignal dataset is published by UCI machine learning repository and can be found [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset). The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

Our aim is to build a machine learning model to be able to identify spam messages. This is similar to how gmail filtersspam emails in your inbox.
#

# Agenda
- Reading the data
- Exploring the data
- Cleaning the data
- Vectorizing the data
- Fit multinomial NB model
- Fit all classifiers using Pycaret AutoML library
- Fit a LSTM nnet
- Compare results
#