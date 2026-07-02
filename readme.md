# AIRLINE PASSENGER REVIEW SENTIMENT ANALYSIS USING MACHINE LEARNING

## Project Overview

This project presents a Sentiment Analysis system that classifies airline passenger reviews as **Recommended (Positive)** or **Not Recommended (Negative)** using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to analyze customer feedback, understand passenger sentiment, and provide valuable insights that can help airlines improve customer satisfaction and service quality.

---

## Project Objectives

* Analyze airline passenger reviews using Natural Language Processing.
* Preprocess textual data for machine learning.
* Convert text into numerical features using TF-IDF Vectorization.
* Build a Logistic Regression model for sentiment classification.
* Evaluate model performance using standard classification metrics.
* Visualize customer sentiment through informative charts and word clouds.

---

## Dataset Information

**Dataset Name:** Airline Reviews Dataset

**Source:** Kaggle

**Description:**

The dataset contains real airline passenger reviews collected from multiple airlines. Each review includes customer feedback, airline information, ratings, travel details, and a recommendation label indicating whether the passenger recommends the airline.

### Dataset Features

| Feature                | Description                              |
| ---------------------- | ---------------------------------------- |
| Airline Name           | Name of the airline                      |
| Overall_Rating         | Overall passenger rating                 |
| Review_Title           | Title of the review                      |
| Review Date            | Date of review                           |
| Verified               | Indicates whether the review is verified |
| Review                 | Passenger review text                    |
| Aircraft               | Aircraft type                            |
| Type Of Traveller      | Passenger category                       |
| Seat Type              | Travel class                             |
| Route                  | Flight route                             |
| Date Flown             | Date of travel                           |
| Seat Comfort           | Seat comfort rating                      |
| Cabin Staff Service    | Cabin crew rating                        |
| Food & Beverages       | Food quality rating                      |
| Ground Service         | Ground service rating                    |
| Inflight Entertainment | Entertainment rating                     |
| Wifi & Connectivity    | WiFi rating                              |
| Value For Money        | Value for money rating                   |
| Recommended            | Target variable (Yes/No)                 |

---

## Technologies Used

| Technology   | Purpose                                            |
| ------------ | -------------------------------------------------- |
| Python       | Core programming language                          |
| Google Colab | Development environment                            |
| Pandas       | Data loading and preprocessing                     |
| NumPy        | Numerical computations                             |
| Matplotlib   | Data visualization                                 |
| Seaborn      | Statistical visualization                          |
| NLTK         | Text preprocessing and Natural Language Processing |
| Scikit-learn | Machine learning and model evaluation              |
| WordCloud    | Word cloud visualization                           |

---

## Project Workflow

```text
Import Libraries
        ↓
Load Dataset
        ↓
Data Cleaning
        ↓
Text Preprocessing
        ↓
TF-IDF Feature Extraction
        ↓
Train-Test Split
        ↓
Logistic Regression Model
        ↓
Model Evaluation
        ↓
Sentiment Prediction
        ↓
Visualization
```

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Missing value analysis
* Removal of unnecessary columns
* Text normalization
* Conversion to lowercase
* Removal of punctuation and special characters
* Stopword removal
* Lemmatization
* TF-IDF Vectorization

---

## Machine Learning Model

**Algorithm Used:** Logistic Regression

### Why Logistic Regression?

* Suitable for binary classification problems.
* Performs efficiently on high-dimensional sparse TF-IDF features.
* Fast to train and predict.
* Easy to interpret.
* Achieved excellent classification performance on the dataset.

---

## Model Performance

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **89.86%** |
| Precision | **0.90**   |
| Recall    | **0.90**   |
| F1-Score  | **0.90**   |

---

## Visualizations

The project includes:

* Sentiment Distribution
* Confusion Matrix
* Positive Reviews Word Cloud
* Negative Reviews Word Cloud
* Custom Review Sentiment Prediction

---

## Key Findings

* The Logistic Regression model achieved an overall accuracy of **89.86%**.
* Most airline reviews in the dataset were negative, indicating class imbalance.
* Text preprocessing significantly improved model performance.
* TF-IDF effectively converted textual reviews into numerical representations.
* Word clouds highlighted frequently occurring positive and negative customer opinions.

---

## Conclusion

This project demonstrates the application of Natural Language Processing and Machine Learning for airline passenger sentiment classification. The developed model successfully predicts customer sentiment from textual reviews and provides valuable insights into passenger experiences. Such sentiment analysis systems can assist airlines in monitoring customer satisfaction and improving service quality.

---

## Repository Structure

```text
CodeAlpha_SentimentAnalysis/
│
├── CODEALPHA_TASK4.ipynb
├── Airline_review.csv
├── README.md
├── requirements.txt
└── images/
    ├── sentiment_distribution.png
    ├── confusion_matrix.png
    ├── positive_wordcloud.png
    └── negative_wordcloud.png
```

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
wordcloud
```

---

## Author

**Syed Sameena Tasleem**

B.Tech – Artificial Intelligence & Data Science

CodeAlpha Data Analytics Intern
