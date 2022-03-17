# Twitter-Sentiment-Classifier
Developed multiple sentiment classifiers, experimenting with models (FFNN, LSTM, GRU, BERT) and word embeddings (TF-IDF, GloVe) for the Twitter dataset.

### Feed-Forward Neural Network Project Description

Develop a vaccine sentiment classifier with 3 classes (neutral, anti-vax and pro-vax) using
feed-forward neural networks and the datasets of the previous homework provided on eclass. We expect you to experiment with at least two models and compare them using
F1 score, recall and precision. For the development of the models, you are expected to
experiment at least with the following hyperparameters:

* the number of hidden layers and the number of their units
* the activation functions
* the loss function
* the optimizer

Furthermore, in at least one of your models, you must use pre-trained word embedding
vectors using GloVe. <br><br>
For your best model, you must also provide the loss vs epochs plot along with the ROC
curve (on the validation set, after training has been completed) and explain what you see.

### LSTM-GRU Project Description

Develop a sentiment classifier with 3 classes (pro-vax, anti-vax, neutral) using a bidirectional stacked RNN with LSTM/GRU cells for the Twitter vaccine sentiment dataset. For the development of the models, you can experiment with the number of stacked RNNs, the number of hidden layers, type of cells, skip connections, gradient clipping and dropout probability. Use the Adam optimizer and the cross-entropy loss function. You should also utilize GloVe pre-trained word embeddings as the embeddings of the inputs of your models. <br><br>
For the best model you will find:

* Compute precision, recall and F1 for each class.
* Plot the loss vs. epochs curve and the ROC curve (on the validation set, after training
has been completed) and explain what you see.

<br><br>

Add attention to the best model you developed in the previous question. Evaluate the
improvements that you might have from its introduction.

### BERT Project Description

Develop a sentiment classifier with 3 classes (pro-vax, anti-vax, neutral) by fine-tuning the
pretrained BERT-base model available on Hugging Face. You have to compute precision,
recall and F1 for each class.

