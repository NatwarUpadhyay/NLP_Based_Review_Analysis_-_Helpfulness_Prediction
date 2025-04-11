# NLP_Based_Review_Analysis_-_Helpfulness_Prediction
This project explores the power of Natural Language Processing (NLP) in analyzing customer sentiments, identifying recent trends in product feedback, classifying review polarity, and predicting review helpfulness!

This Natural Language Processing (NLP) project is focused on analyzing user reviews for the iPhone 11 scraped from Flipkart, in order to extract valuable business insights, build automated sentiment classification models, and predict review helpfulness. The project simulates real-world business queries and helps build end-to-end pipelines for actionable review analytics.
🧾 Dataset Overview

    Product: Apple iPhone 11 – 128GB Black

    Source: Flipkart (via custom Python scraping script)

    Collected Attributes: Review title, body, date, rating, helpful votes, verified purchase tag, image attachment status


💼 Project Breakdown
📌 Review Insights Analysis (review_insights_analysis.py)

Goal: Explore all collected reviews to identify prominent issues and sentiments.

    Text pre-processing with lemmatization, stopword removal

    Keyword frequency and thematic patterns

    Findings:

        Highly positive reception for camera and authenticity

        Negative feedback focused on delivery and battery performance

📌 Recent Trend Monitoring (recent_trend_analysis.py)

Goal: Re-analyze the most recent 25% of reviews to uncover new customer concerns.

    Sorted reviews by date and segmented latest 25%

    Reapplied NLP methods to extract updated sentiment themes

    Observations:

        Increased mention of iOS compatibility issues and device heating

        Persistent issues with delivery and packaging experience

📌 Sentiment Classification (sentiment_classifier.py)

Goal: Build a machine learning model to classify review sentiment.

    Labeled reviews based on star rating polarity

    Feature extraction using TF-IDF and other techniques

    Applied classification algorithms and evaluated performance

    Final model supports real-time positive/negative tagging of reviews

📌 Helpfulness Prediction (helpfulness_prediction.py)

Goal: Predict the number of helpful votes a review may receive.

    Features included sentiment, length, recency, and image attachments

    Models trained to predict normalized helpfulness score

    Key factors:

        Reviews with higher emotional tone and image attachments are often marked more helpful

🛠️ Tools & Libraries

    Python, Pandas, NumPy

    BeautifulSoup, Selenium (for scraping)

    NLTK, SpaCy, TextBlob

    Scikit-learn, XGBoost

    Matplotlib, Seaborn

📌 Business Use Cases Addressed

    Insight Mining for product improvement

    Feedback Monitoring for trend changes

    Auto-Classification for review moderation or flagging

    Helpfulness Scoring to rank top reviews on e-commerce listings

📝 Future Enhancements

    Expand scraping across other platforms (Amazon, Myntra).

    Use BERT or LLM-based classification models.

    Deploy classifier and helpfulness model as REST APIs.


🤝 Contributing
Pull requests and feature suggestions are welcome! For major changes, please open an issue first.
