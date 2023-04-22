# Goodreads
Rating classification on large GoodReads Review data set only using google collab
In this project, we built a deep learning model that is used to predict the review rating of a book
review that ranges from 1 to 5. We used the Goodreads dataset that contains reviews from
Goodreads which is a website for book reviews. It contains 900000 book reviews from about
25,475 books and 18,892 users.
Only google collab was used
Different methods such as TFIDF followed by Truncated Singular Value decomposition
and a 1D CNN using glove embeddings
You can upgrade to google collab pro and use higher dimensions for the glove embeddings or increase the Trunc SVD dimensions
Highest Accuracy was 58.5% using 1D CNN with 300 dimension Glove embeddings
On only 40,000 reviews.
Very simple LSTM with Truncated SVD and TFIDF produced similar results when increasing dimension size
High potential if LSTM model is made more complex or optimized
Very promising if there are major computational constraints 
