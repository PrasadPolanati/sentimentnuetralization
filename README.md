
## Sentiment Classification ##
LSTM model for sentiment classification which involves self attention.

This takes parameters from *neutralisation_params.py* file. This builds a classifier which classifies sentences into Positive and Negative. The input here is a csv file such as *sentiment_data.csv* which requires 2 columns, text and label.

## Sentiment Neutralization ##
The words which receive most attention in the sentiment classification task are removed for Sentiment Neutralization
This loads the model and pickle saved by previously run classification code and removes the words which had high attention depending on the label. It reads data from *dataSampleTest.csv* file which has 2 columns namely : phrase & Actual Negative
