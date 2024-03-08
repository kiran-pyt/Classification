
# US Economic News Classification

## Overview
This project aims to classify US economic news articles as relevant or not relevant based on their content. The dataset used contains textual data along with their relevance labels.

## Dataset
The dataset used in this project is called `US-Economic-News.csv`. It contains text data and relevance labels. Some preprocessing steps were applied to clean the text data, including:
- Converting text to lowercase
- Removing HTML tags
- Removing URLs
- Removing punctuations and digits
- Removing stop words
- Lemmatization

## Dependencies
- Python 3
- Libraries: pandas, numpy, matplotlib, plotly, seaborn, beautifulsoup4, nltk, scikit-learn

## Files
- `US-Economic-News.csv`: Dataset containing text data and relevance labels.
- `classification_project.ipynb`: Jupyter Notebook containing the code for data preprocessing, exploratory data analysis, and classification model training and evaluation.

## Preprocessing
The text data underwent several preprocessing steps to clean and prepare it for classification:
1. Conversion to lowercase
2. Removal of HTML tags
3. Removal of URLs
4. Removal of punctuations and digits
5. Removal of stop words
6. Lemmatization

## Model Training
- TF-IDF Vectorization: The textual data was transformed into TF-IDF vectors.
- Gaussian Naive Bayes Classifier: The TF-IDF vectors were used to train a Gaussian Naive Bayes classifier.
- Train-Test Split: The dataset was split into training and testing sets using an 80-20 split.

## Results
- The Gaussian Naive Bayes classifier achieved an accuracy of X% on the training set and Y% on the testing set.
- Classification report and confusion matrix were generated to evaluate the performance of the classifier.

## Conclusion
The classification model showed promising results in distinguishing between relevant and not relevant US economic news articles based on their content.

---

Feel free to customize it further based on your specific project details!
