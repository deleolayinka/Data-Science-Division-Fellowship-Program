# Data-Science-Division-Fellowship-Program

## Dataset
This data set was produced by the company figure-eight and was first made available on their "Data for Everyone" [website](https://appen.com/pre-labeled-datasets/).

### Files
**sample_submission.csv** - a sample submission file in the correct format

**train.csv** - the training set

**test.csv** - the test set


### Columns
**id** - a unique identifier for each tweet

**text** - the text of the tweet

**location** - the location the tweet was sent from (may be blank)

**keyword** - a particular keyword from the tweet (may be blank)

**target** - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

## Future Exploration
This notebook explored a limited number of algorithms, methodologies, and models. In practice, it is not uncommon to test over hundreds or even higher number of models. Some other ways that would help us find the best model to solve the given NLP problem include:

- Using different vectorizers (e.g., Word2Vec, N-grams)
- Exploring the accuracy of the proper and improper nouns variables created in **Task 2** using the nltk library, considering alternatives such as spaCy, an open-source software library for advanced natural language processing, written in the programming languages Python and Cython.
- Including parts of the text we removed from the modelling (e.g., stopwords)
- Exploring different hyperparameter settings within each algorithm (e.g., adding 'max_features' parameter and a few possible values of it to the RandomizedSearchCV object)
- Using different hyperparameter optimization methods (e.g., Bayesian method using Optuna)
