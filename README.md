# Sentiment Analysis using Naive Bayes

This project demonstrates a simple sentiment analysis implementation using the Naive Bayes algorithm. The code was developed in Jupyter Notebook and can classify text as positive, negative, or neutral based on a dataset.

## Features

- **Training**: Uses labeled data to train the Naive Bayes classifier.
- **Prediction**: Classifies user-provided text.
- **Evaluation**: Includes metrics to evaluate the model's performance.
  
---

## Setup and Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Manas303-debug/Sentiment-Analysis-with-Naive-Bayes.git
   cd Sentiment-Analysis-with-Naive-Bayes
pip install -r requirements.txt

# Project Overview

## Data Collection  
This project utilizes a dataset comprising user reviews and corresponding star ratings sourced from a course-selling website. The dataset reflects the sentiment and opinions of users, enabling the model to learn and predict ratings based on textual feedback.

---

## Text Preprocessing  
The raw text data undergoes a series of preprocessing steps to ensure it's ready for analysis:  
- **Stopword Removal**: Eliminates commonly used words (e.g., "the", "and") that do not contribute to sentiment classification.  
- **Punctuation Handling**: Strips unnecessary punctuation to focus on meaningful text.  
- **Text Transformation**: Converts text into numerical features using techniques like bag-of-words (BoW) or TF-IDF (Term Frequency-Inverse Document Frequency). These features serve as input for the Naive Bayes classifier.

---

## Naive Bayes Model  
A **Naive Bayes Classifier** is implemented to analyze the processed text data and predict star ratings. The model leverages the probabilistic nature of Naive Bayes, making it particularly effective for text classification tasks. Key highlights of the model include:  
- Efficient handling of sparse data.  
- Robust performance even with relatively small datasets.  
- Ability to generalize well to unseen data.

---

## Model Evaluation  
The performance of the classifier is rigorously assessed using industry-standard metrics:  
- **Accuracy**: Measures the percentage of correctly predicted reviews out of the total.  
- **Precision**: Evaluates the proportion of true positive predictions among all positive predictions.  
- **Recall**: Assesses the model's ability to identify all relevant positive instances.  
- **F1-Score**: A harmonic mean of precision and recall, offering a balanced evaluation metric.  

A confusion matrix and classification report are generated to provide deeper insights into the model's predictions and error patterns.

---

## Interactive Jupyter Notebook  
The entire process—from data loading to model evaluation—is thoroughly documented in an interactive **Jupyter Notebook**. This format allows for:  
- **Step-by-Step Guidance**: Each step is clearly explained, making it easy for users to follow the process.  
- **Reproducibility**: Users can run the notebook on their own systems with minimal setup to replicate results.  
- **Customization**: The notebook supports experimentation with different datasets, preprocessing techniques, and model parameters.  

---

This structure not only outlines the key components of the project but also ensures clarity and accessibility for users at all levels. Let me know if you'd like any further tweaks! 😊

