# Sentiment-Analysis-from-Amazon-Reviews
This is a project of sentiment analysis from text.  
Dataset used is from https://www.kaggle.com/datasets/bittlingmayer/amazonreviews  
## Pre-processing
In the pre-processing part, reviews are cleaned and word vectors are built using Word2Vec from gensim.  
## Models and Results  
**Model**|**Accuracy**|**Loss**|**Training Time**
:--:|:--:|:--:|:--:
CNN (Convolutional Neutral Network)|94.150%|0.159|15.97 min
LSTM (Long Short Term Memory)|94.150%|0.166| about 2 hours
GRU (Gate Recurrent Unit)|94.917%|0.137|22.58 min 

Therefore, GRU is chosen as the final model, because it has higher accuary and relatively shorter training time.  

Please see notebooks for detail.
