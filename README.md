# Recommender

Melbourne Restaurant/Cafe Recommender System
--------------------------------------------

With the ever-growing competition in the restaurant and café industry, how can a business maintain, and better yet increase, its share of the market?

On the part of the consumer, how does one continue to make worthy purchasing decisions despite the rising number of choices in this crowded restaurant and café scene?

The answer: Restaurant Recommender System.

It allows the diners to discover restaurants based on their preferences and purchase history by providing personalized recommendations

It helps restaurant/café owners in acquiring new customers as well as maintain engagement with existing ones

The main goals of this recommender system are as follows:
1. Provide top-n restaurant recommendations to users based on multiple recommender algorithms
2. Predict the rating that a user would give an unrated restaurant
3. Evaluate the rating prediction and identify the top-performing recommender technique based on the evaluation results.

The dataset is from the top restaurant review site, Zomato, and particularly its 'Best of Melbourne' collection. The dataset totals to 30475 reviews, gathered from 253 restaurants, and it was obtained via web scraping and API access methods. 

The recommendation techniques used are as follows:
1. Content-Based Filtering
2. User-Item Collaborative Filtering (pairwise-cosine distance)
3. Item-Item Collaborative Filtering (pairwise-cosine distance)
4. Item-Item Collaborative Filtering - Top-N Recommendation and Rating Prediction (pairwise-cosine distance)
5. Item-Item Collaborative Filtering - Top-N Recommendation and Rating Prediction (pairwise-cosine Similarity)
6. Hybrid Recommender - User-Item CF & Content-Based
7. Hybrid Recommender - Item-Item CF & Content-Based
8. Rating Prediction and Evaluation for Entire Matrices using Memory-Based CF
9. Rating Prediction and Evaluation for Entire Matrices using Model-Based CF - Scipy SVDS (Matrix Factorization)
10. Rating Prediction and Evaluation for Individual User-Restaurant Pair using - Surprise SVD (Matrix Factorization)
11. Recent Favorites Recommendation
12. Most Popular Recommendation

Some of the tools and libraries used are as follows:
- Surprise
- Scipy
- Web Scraping
- Selenium
- Scrapy
- XPath
- Zomato API
- Google Maps API
- Geopy
- Geocoder
