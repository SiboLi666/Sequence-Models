# Sequence-Models - Coursera deeplearning.ai course

## Project 1: Building a Recurrent Neural Network Step by Step
In this practice, I implemented key components of a Recurrent Neural Network in numpy.

Recurrent Neural Networks (RNN) are very effective for Natural Language Processing and other sequence tasks because they have "memory". They can read inputs  x⟨t⟩x⟨t⟩  (such as words) one at a time, and remember some information/context through the hidden layer activations that get passed from one time-step to the next. This allows a unidirectional RNN to take information from the past to process later inputs. A bidirectional RNN can take context from both the past and the future.

## Project 2: Character level language model - Dinosaurus Island
To create new dinosaur names, I build a character level language model to generate new names. My algorithm will learn the different name patterns, and randomly generate new names. I begin by loading in some functions provided in rnn_utils. Specifically, you have access to functions such as rnn_forward and rnn_backward which are equivalent to those I've implemented in the Project 1.

## Project 3: Implement a model that uses an LSTM to generate music

## Project 4: Operations on word vectors
- Load pre-trained word vectors, and measure similarity using cosine similarity
- Use word embeddings to solve word analogy problems such as Man is to Woman as King is to __.
- Modify word embeddings to reduce their gender bias

## Project 5: Emojify
- Start with a baseline model (Emojifier-V1) using word embeddings.
- Then build a more sophisticated model (Emojifier-V2) that further incorporates an LSTM.

## Project 6
- Build a Neural Machine Translation (NMT) model to translate human-readable dates ("25th of June, 2009") into machine-readable dates ("2009-06-25").

## Project 7
- Build a Neural Machine Translation (NMT) model to translate human-readable dates ("25th of June, 2009") into machine-readable dates ("2009-06-25").
- Do this using an attention model, one of the most sophisticated sequence-to-sequence models.
