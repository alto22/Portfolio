# Song_Genre_Classification


> MSc Business Administration and Data Science

> Submission Date: 29.05.23

## Data Download

- [Google Drive](https://drive.google.com/drive/folders/1wLfo7MXIsO2Cl7cxPL8HBGq_QvnmTqPF)

## Authors
- David Bellenberg
- Alexander Mealor
- Alexander Ries
- Aleksander Torp


## Abstract
This paper investigates the applicability of machine learning for determining a song’s genre based solely on lyrics. We implement five different combinations of models and word embedding techniques on a dataset of more than three million English songs spanning the genres pop, rap, rock, r/b, and country. The benchmark model is a Naive Bayes with Bag-of-Word vectorization which is compared against a Logistic Regression with TF-IDF vectorization, Random Forest and Long Short-Term Memory neural network with Word2Vec embeddings, and a BERT classifier. We find that the most complex model and embedding combination, BERT, provides the strongest classification performance in terms of macro average scores for both precision, 0.69, and recall, 0.61, across all genres. The results suggest that song lyrics may provide a solid foundation for classifying music genres. We propose an interactive user-interface incorporating our best performing model for real-time genre classification in the context of providers for music streaming.

Keywords: Lyrics, Text Classification, Naive Bayes, Logistic Regression, Random Forest, Word2Vec, LSTM, BERT
