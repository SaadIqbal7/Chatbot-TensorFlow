# Chatbot TensorFlow

This repository contains a Jupyter Notebook for traning a Chatbot using Seq2Seq model with Attention.

Follow this drive [link](https://drive.google.com/drive/folders/1cEcA2wRek9NKbZ5h0dKjUJY7hfmkwv-z?usp=sharing) to get training, validation and test set for training the model. The training set contains 315131 examples, validation set contains 1591 examples and test set contains 1593 examples. The dataset was curated using 4 chatbot datasets, random shuffled to make the dataset asymmetric and divided in train, validation and test sets.

The drive link also contains glove 50 dimensional word embeddings which is used in this Notebook. You can download this embedding or you can follow this link https://nlp.stanford.edu/projects/glove/ to download word embeddings of different dimensions. Use
```
load_from_glove_vector(path_glove)
```
helper function to load the glove word embeddings of any dimension.
