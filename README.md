# Hate Speech Detection - Text Analytics
## Overview

This project focuses on detecting hate speech using text analytics. The primary goal is to classify instances of harmful content, including hate speech, abuse, and negative stereotypes, using the OLID (Offensive Language Identification Dataset). 

## Project Description

The project involves preprocessing and analyzing text data to classify hate speech. Two classification algorithms, Support Vector Machine (SVM) and Multinomial Logistic Regression (MLR), were implemented and compared. The key tasks included data preprocessing, feature extraction, model training, and performance evaluation.

### Key Tasks

1. **Dataset Handling:**
   - Utilized the OLID dataset, which includes various forms of offensive language.
   - Split the dataset into training, validation, and test sets.

2. **Data Preprocessing:**
   - Used Natural Language Toolkit (NLTK) for text feature processing and preprocessing.
   - Applied count vectorization to convert text data into numerical features.

3. **Model Implementation:**
   - Implemented Support Vector Machine (SVM) and Multinomial Logistic Regression (MLR) classifiers for hate speech detection.
   - Fine-tuned model hyperparameters to optimize performance.

4. **Performance Evaluation:**
   - Compared the performance of SVM and MLR using metrics such as F1-score, precision, recall, and accuracy.
   - Evaluated the models on different dataset sizes (25%, 50%, 75%, 100%) to assess the impact of data size on classification performance.

5. **Multilingual Testing:**
   - Conducted text analysis on multilingual datasets to evaluate the models' effectiveness across different languages.
   - Analyzed and compared results for datasets in Portuguese, German, Chinese, English, and Dutch.

## Results

- **Model Performance:**
  - Both SVM and MLR achieved similar F1 scores, indicating comparable performance.
  - SVM demonstrated slightly higher accuracy in some cases.

- **Impact of Data Size:**
  - Model performance improved with larger datasets, showing better precision, recall, and F1-scores as more data was used.

- **Multilingual Performance:**
  - Performance varied across different languages, with the highest F1 scores achieved in Portuguese and German datasets.

## Technologies Used

- **Natural Language Toolkit (NLTK):** For text preprocessing and feature extraction.
- **Scikit-learn:** For implementing SVM and MLR classifiers.
- **Python:** Primary programming language used for the project.
