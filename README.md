# bbc-news-classification


DATASET LINK 

BBC News Dataset: A dataset of 2,225 news articles labeled as one of 5 categories, such as business, entertainment, politics, sport, and tech. The dataset can be downloaded from https://www.kaggle.com/c/learn-ai-bbc/data


Steps follwed

Preprocessed and tokenized datasets in the form of train_encodings, val_encodings, and test_encodings dictionaries containing the encoded text samples and their corresponding labels.


The model training history, including the loss and accuracy for each epoch, printed to the console.


Evaluation metrics such as accuracy, precision, recall, and F1-score, printed to the console, indicating the performance of the trained model on the test set.


A confusion matrix plot showing the number of true positive, false positive, true negative, and false negative predictions for each class.


The predictions of the trained model for a few randomly selected samples from the test set, including the original text, the true label, and the predicted label.


The fine-tuned model saved to disk as a file, which can be loaded and used for making predictions on new data.


A summary of the model architecture and the number of trainable parameters, printed to the console.

The output of the code will be the training and validation loss and accuracy at the end of each epoch, as well as the final accuracy score on the test set. The exact output will vary depending on the random seed used for the train-test split and the initializations of the model parameters.



