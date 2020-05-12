# Multi-label toxic comment classification - NLP Project ENSAE 2020

Our work aims to classifity toxic comments (multi-label and multi-class toxic comment classification). We have processed the texts of the comments using three different embedding vectorizers for sentence embedding (TF-IDF, Doc2Vec) and words embedding (Word2Vec). In order to improve our embedding we have used transfer learning to pre-trained our Word2Vec model. We also tried to create new features to improve our model. For the classification of the toxicity of the comments, we have used two classic models, logistic regression and LGBM, which allow to make independent classification for each of the class of toxicity. Then, we have used an bidirectional LSTM model which can process multi-class aand multi-label classification. Our model is tested on 63978 comments which coome from Wikipedia.

## Get started with the code

1. First you need to pip install tensorflow==1.15 and pip install tensorflow-gpu==1.15 in Google Colab environment because by default Google Colab uses tensorflow 2.X (some changes on version 2.X cause problems with our code)

2. Open the notebook with Google Colab

3. Change to GPU mode and run it (it may take hours to run the notebook)

## Authors

* Eleonore Blanchard
* Yannick Ly


 
