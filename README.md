# Arabic Sentiment Analysis on Twitter Corpus

Sentiment classification (Positive/Negative) of Arabic tweets using Naive Bayes with CountVectorizer and TF-IDF.

## Dataset

- Source: Arabic tweets corpus
- Positive tweets: 1,000+ (test file)
- Negative tweets: 1,000+ (test file)

## Arabic Text Preprocessing

| Step | Operation |
|------|-----------|
| 1 | Remove URLs, mentions, hashtags |
| 2 | Remove diacritics (Arabic vowels) |
| 3 | Remove elongation (word elongation) |
| 4 | Remove numbers & punctuation |
| 5 | Normalize letters (إأآ → ا, ى → ي, ة → ه, ئؤ → ء) |
| 6 | Remove Arabic stopwords |
| 7 | Remove extra whitespace |

## Models & Results

| Vectorizer | Model | Accuracy |
|------------|-------|----------|
| CountVectorizer | Multinomial Naive Bayes | ~74.4% |
| TF-IDF | Multinomial Naive Bayes | ~74.4% |

## Author

Fatma Abdullah


## License

Open source
