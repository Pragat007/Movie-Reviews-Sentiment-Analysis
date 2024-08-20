# Movie-Reviews-Sentiment-Analysis

This project is focused on performing sentiment analysis on a built-in corpus in NLTK, specifically the Movie Reviews dataset. The dataset contains positive and negative movie reviews, which are used to train various classifiers for sentiment prediction.

## Project Overview

The goal of this project is to preprocess the text data by reducing unnecessary words using techniques like lemmatization, removing stopwords, and filtering out punctuation. The processed text data is then used to extract features based on word frequency and probability. These features are utilized to train and test three different classifiers:

- **Naive Bayes Classifier**
- **Support Vector Classifier (SVC)**
- **Random Forest Classifier**

### Results

The accuracy achieved by each classifier on the test data is as follows:

- **Naive Bayes Classifier:** 79%
- **Support Vector Classifier (SVC):** 85.8%
- **Random Forest Classifier:** 79%

## Features

- **Text Preprocessing:** 
  - Lemmatization to reduce words to their base form.
  - Removal of stopwords and punctuation.
- **Feature Extraction:** 
  - Frequency and probability of word counts are used as features.
- **Model Training:** 
  - Models are trained using the extracted features to predict the sentiment of reviews.

## Installation

To run this project locally, you'll need to have Python installed, along with the following packages:

```bash
pip install nltk scikit-learn
```

You can clone this repository using the following command:

```bash
git clone https://github.com/Pragat007/Movie-Reviews-Sentiment-Analysis
```

## Usage

1. **Preprocess the Data:** The corpus is preprocessed to remove stopwords, punctuation, and to lemmatize the text.
2. **Feature Extraction:** Extract features based on word frequency and probability.
3. **Train the Models:** Train the Naive Bayes, SVC, and Random Forest classifiers using the extracted features.
4. **Evaluate the Models:** Test the models on unseen data and compare their accuracy.

To run the analysis, execute the provided Jupyter notebook:

```bash
jupyter notebook movie_review.ipynb
```

## Project Structure

- **movie_review.ipynb:** The Jupyter notebook containing the full analysis, including data preprocessing, feature extraction, model training, and evaluation.
- **README.md:** Project documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The NLTK library for providing the Movie Reviews dataset and various NLP tools.
- The Scikit-learn library for providing machine learning models and utilities.
