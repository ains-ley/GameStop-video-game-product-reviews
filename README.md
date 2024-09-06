**Goal:** Analyze how the sentiment and content of GameStop’s video game product reviews influence customer recommendations and product ratings

**Tools:**
- Pandas: used for data manipulation and analysis
- TextBlob: used for sentiment analysis
- Matploblib: data visualization (visualizing correlations between sentiment scores, ratings and recommendations)
- WordCloud: used for generating word clouds from the text in reviews, creating visual representations of common words in both negative and positive reviews

**Key Findings:**
1. Sentiment and Product Ratings:
   - Moderate positive correlation (0.375): customers who express positive sentiment tend to give better ratings.
   - Not perfect alignment: some reviews with neutral or negative sentiment still have moderate or even positive ratings, indicating other factors like gameplay experience or franchise loyalty influence the ratings.
2. Sentiment and Recommendations:
   - Weaker Correlation (0.253): sentiment does not play a significant role in influencing recommendations.
   - Negative sentiment with recommendations: many customers recommend a product despite negative sentiment.
   - Positive sentiment without recommendations: despite positive sentiment, some reviews don’t result in recommendations.
3. Review Content Patterns:
   - Negative reviews with recommendations: specific game titles (e.g., Pokemon, Fallout) and terms like “fun” and “recommend” suggest that customers are recommending games despite complaints because of overall entertainment value.
   - Positive reviews without recommendations: Terms like "graphics," "challenging," and "mechanics" show that while customers appreciate aspects like graphics, they are hesitant to recommend the product due to certain gameplay issues or unmet expectations.
