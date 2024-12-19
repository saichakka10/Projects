## Amazon Kindle Sentiment Analysis
This project involves analyzing customer sentiments from Amazon Kindle reviews using natural language processing (NLP) techniques. 
The primary techniques employed include Bag of Words (BoW), TF-IDF, and Word2Vec, implemented in three separate files corresponding to each technique.

# Dataset Description
* The dataset contains multiple columns: Unnamed, asin, helpful, overall, reviewText, reviewTime, reviewerID, reviewerName, summary, unixReviewTime.
Key steps include:
1. Extracted the relevant columns: reviewText (the customer reviews) and overall (ratings).
2. Renamed the overall column to rating for further usage in the code.
3. Checked for null values in the dataset. Any rows containing null values were removed to ensure data quality.
4. Created a sample dataset of 0.05% of the original dataset for the analysis
