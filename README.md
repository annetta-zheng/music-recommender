# music-recommender
Sentiment Analysis and Music Recommendations Systems
Description: a review-based recommendation system with natural language processing (NLP) and Collaborative Filtering on 1.5M review data and 75k music meta data, utilizing Python via keras framework on an AWS EC2 instance.

1. Trained a convolutional neural network (CNN) for Sentiment Analysis on the review texts classifying the reviews as positive and negative, summarized keyword using NLTK, visualized word embeddings, and gained 91.4% test accuracy.

      <img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599514-0c6ab305-e115-403f-bf68-8135e06a339b.png">

      The most significant words in review texts:
<img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599154-f5964ddd-9138-49c9-8e1b-fd5b70d0f30f.png">

      The most significant words in summary texts:
<img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599389-b72f1da1-b877-4eab-88c0-74d2500b6908.png">

2. Trained a stacked Autoencoder with SGD on tokenized and embedded text matrix for dimensionality reduction.
      <img width="432" alt="image" src="https://user-images.githubusercontent.com/67286396/204599574-3ae71217-c4e7-40e4-a336-ee15429344c3.png">
      
3. Trained a Deep Neural Network with regularization for the recommender with MAE below 0.4 and MSE below 40.
      <img width="808" alt="image" src="https://user-images.githubusercontent.com/67286396/204600119-0ae46ce1-43fb-4221-9ae4-3b4507817285.png">
