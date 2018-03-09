# Deep_Learning_for_NLP
Jupyter notebooks for "Deep Learning for NLP" workshop

## Requirements
The following requirements are to be satisfied for executing the following jupyter notebooks.

The machine should have python 3.6 installed

For interactive computing, install Jupyter notebook. To install juypter notebook, issue the following commands in your terminal

`pip3 install --upgrade pip`

`pip3 install jupyter`

Install gensim, NLTK

`pip3 install --upgrade gensim` (Run in sudo or admin mode based on your OS)

`pip3 install NLT`

Download NLTK data using the following command

`sudo python -m nltk.downloader -d /usr/local/share/nltk_data all`

You can download Google News pre-trained vectors from the following link (OPTIONAL)
   https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit

Install Tensorflow for python on your machine. To do so please follow the instructions in the given link based on your OS. (GPU installation is optional)
   https://www.tensorflow.org/install/
   
Install keras by issuing the following command

`pip3 install keras`
   
To host the jupyter notebooks as a local webapp, make this your working directory and run *jupyter notebook*

## Contents
1. Introduction to Natural Language Processing gives you a quick walkthrough of NLP
2. Introduction to Deep Learning gives a quick introduction to Deep Learning
3. Word Embeddings gives an introduction to word embeddings and various sources of info
4. Word2Vec gives an introduction on how to train a Word2Vec 
5. Word2Vec-Workbook gives an example on how to train a Word2Vec model using gensim
6. LinearRegression gives an introduction to TensorFlow with a simple implementation of Linear Regression using TensorFlow
7. Simple LSTM has an example of Language Modeling using LSTM Recurrent Neural Networks with a single hidden layer
8. LSTM 2 layer has an example of Language Modeling using LSTM Recurrent Neural Networks with 2 hidden layers.
