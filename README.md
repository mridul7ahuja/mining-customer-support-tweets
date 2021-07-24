# Customer Support Data on Twitter
Preprocessed tweets by stemming, lemmatization and removal of punctuations, stopwords and emojis and conducted exploratory data analysis. 
Used continuous-bag-of-words and skip-gram model of word2vec to learn word embeddings along with topic modelling using Latent Dirichlet Allocation (LDA) and biterm-models. 
Also conducted phrase-based categorization and sentiment analysis. 

## few interesting results
Around the date of the release of iPhone X, the number of inbound tweets to AppleSupport sharply increases and there is an overall improvement in customer sentiment. 

![apple_iphone](https://user-images.githubusercontent.com/58695866/126881345-e905b650-09b8-4fe5-9cd8-fb8c782971bd.PNG)

Results from sentiment analysis:
![sentiment_by_brand](https://user-images.githubusercontent.com/58695866/126880313-0b78de52-1d61-46a0-bf51-d0c060c37a04.PNG)

Using the embeddings learned through the word2vec model, we can query for analogies such as, "spotify" is to a "song" as "xbox" is to a "game"

![analogy_spotify](https://user-images.githubusercontent.com/58695866/126880227-3f8df669-1bd4-4a77-a515-0714004a334c.PNG)

We can also query the model for words similar to a given input such as for 'apple', 'applesupport', 'iphone' and 'applenews' is expected.

![sim_apple](https://user-images.githubusercontent.com/58695866/126880238-0969d03d-c57a-4f37-8228-d95a9316c612.PNG)

