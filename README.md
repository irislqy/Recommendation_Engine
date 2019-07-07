# Recommendation Engines

![](https://media.giphy.com/media/3og0ICZh82LEsNjHoc/giphy.gif)


Recommendation systems are widely applied in business. Retailers largely adopt recommendation engine online to do cross-selling for products. The "Guess What You Also Like" is the most representative case. Recommendation is also playing an important role in revenue growth in Netflix. By integrating recommendation contents on the interface, netflix users probably are lured into a next movie which they did not plan to watch. 


This notebook uses MovieLens 20M Dataset. It contains 20000263 ratings and 465564 tag applications across 27278 movies. Data is collected from https://www.kaggle.com/grouplens/movielens-20m-dataset/downloads/movielens-20m-dataset.zip/1. 

Table of Content
  1. Ingest
  2. Data Preparation
  3. Observational Data Analysis
    3.1. Distribution of Ratings - 1
    3.2. Distributiong of Ratings - 2
    3.3. Exploration of Genres
  4. Recommendation Engines: Model Building
    4.1. Install Packages
    4.2. Collaborative Filtering: User-based
    4.3. Pearsons'r: Item-based
    4.4. kNN: Item-based
  5. Conclusion
  

  
  
