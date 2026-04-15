# Reddit Sentiment Streaming Pipeline | Kafka Â· PySpark Â· MongoDB Â· NLP

> **Type:** Streaming | **Stack:** Reddit PRAW â†’ Kafka â†’ PySpark â†’ MongoDB â†’ BigQuery â†’ Airflow

## Key Metrics
- **200â€“500 posts/hour** processed in real-time
- **<60 seconds** end-to-end latency
- **VADER + TextBlob ensemble** NLP for higher accuracy
- **5 subreddits:** r/technology, r/datascience, r/MachineLearning, r/programming, r/Python

## Sentiment Model
```
ensemble_score = (vader_compound + textblob_polarity) / 2
positive: score >= 0.05
neutral:  -0.05 < score < 0.05
negative: score <= -0.05
```

## Tech Stack
Python Â· PRAW Â· Apache Kafka Â· PySpark Â· VADER Â· TextBlob Â· MongoDB Â· BigQuery Â· Airflow Â· Docker

## Author
**Ahmad Zulham Hamdan** | [LinkedIn](https://linkedin.com/in/ahmad-zulham-hamdan-665170279) | [GitHub](https://github.com/zulham-tech)
