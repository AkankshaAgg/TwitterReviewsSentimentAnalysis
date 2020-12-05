# TwitterReviewsSentimentAnalysis

Sentiment analysis of twitter reviews using NLP with BERT. Positive (1) or Negative (0) in terms of feeling. 
CNN is used for classification. Also, different tools that we have with bert are: 
1. Bert tokenizer 
2. Bert as an embedder
Dataset contains lakhs of twitter reviews.

For Bert tokenizer:
* Training accuarcy - 88.73%
* Test accuracy - 81.21% 
* More overfitting

For bert as an embedding layer:
* Bert layer contains 3 different types of inputs i.e. 3 different types of tokens for each sentence: ids, masks and segments.
* Training accuracy - 84.59% 
* Test accuracy - 85.74% 
* Less overfitting 
