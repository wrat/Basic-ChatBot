#Chatbot
Basic Chatbot Generative Model(Tensorflow)

Overview
============
Given ChatBot Generative model is typically based on Machine Translation techniques, but instead of translating from one language to another, we “translate” from an input to an output (response).
In this given code, we implement Tensorflows [Sequence to Sequence](https://www.tensorflow.org/versions/r0.12/tutorials/seq2seq/index.html) model to train a chatbot on the [Cornell Movie Dialogue dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html). After training for a few hours, the bot is able to hold a fun conversation.

Dependencies
============
* numpy
* scipy 
* six
* tensorflow

Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``
