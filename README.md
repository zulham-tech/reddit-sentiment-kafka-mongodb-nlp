# Reddit Sentiment Streaming Pipeline | Kafka, PySpark, MongoDB, NLP

**Stack:** Reddit PRAW -> Kafka -> PySpark -> MongoDB -> BigQuery -> Airflow

## Key Metrics
- 200-500 posts/hour processed in real-time
- Less than 60 seconds end-to-end latency
- VADER + TextBlob ensemble NLP for higher accuracy
- 5 subreddits: r/technology, r/datascience, r/MachineLearning, r/programming, r/Python

## Sentiment Model
```
ensemble_score = (vader_compound + textblob_polarity) / 2
positive: score >= 0.05
neutral:  -0.05 < score < 0.05
negative: score <= -0.05
```

## Tech Stack
Python, PRAW, Apache Kafka, PySpark, VADER, TextBlob, MongoDB, BigQuery, Airflow, Docker

## Author
Ahmad Zulham Hamdan | https://linkedin.com/in/ahmad-zulham-hamdan-665170279