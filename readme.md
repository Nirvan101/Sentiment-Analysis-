The dataset contains dialogues from the show 'Friends'. The dialogues are classified into 'NEGATIVE', 'POSITIVE', 'NEUTRAL' and 'MIXED' based on their sentiment. This model performs sentiment analysis over these 4 classes. I have used an LSTM to read the words as tokens and an Embedding layer to convert them to word vectors. The final prediction is done using a Dense layer and softmax activation.

I had found that the number of datapoints from different classes was heavily unbalanced. So during preprocessing, I have copied some data points to balance the dataset.
