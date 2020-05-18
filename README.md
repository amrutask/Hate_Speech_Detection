# Hate_Speech_Detection

## Classification of tweets on Twitter Dataset

## Description
The project is about the classification of tweets of twitter dataset into three categories:
1. Hate Speech - Speech based on race, religion, sex, or sexual orientation
2. Offensive language - Use of foul or abusive language
3. Neither - Normal tweets

## Technologies
* NLP techniques for feature respresentation
* LSTM
* CNN
* Keras
* Glove Embeddings

## Models
### Developed three models using bidirectional LSTM and CNN to perform classification of tweets of twitter dataset into three categories: hate speech, offensive language and neither.

* Generated feature representations of the tweets using index representation and passed the dataset to bidirectional LSTM with random embedding for model 1 and with pretrained glove embeddings for model 2 with Softmax at the end.
* Created character level representations for tweets using character to index mapping and used one-hot embeddings in 4 CNN+ ReLU with 3 Max pooling layers in between followed by 3 fully connected layers with Softmax at the end.

Method 1: Use of random word embeddings to train bi-directional LSTM in keras
Method 2: Use of pretrained glove embeddings to train bi-directional LSTM
Method 3: Character level embedding in Convolutional Neural Network (CNN)
