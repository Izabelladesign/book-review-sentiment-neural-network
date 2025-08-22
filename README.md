# Book Review Sentiment Analysis with Neural Networks

This project applies a complete machine learning workflow to predict the sentiment (positive or negative) of book reviews using neural networks and natural language processing (NLP) techniques.

---

## Data Preprocessing

- Cleaned and normalized review text  
  (e.g., lowercasing, removing punctuation and special characters)
- Transformed text data into numerical features using TF-IDF vectorization

---

## Exploratory Data Analysis (EDA)

- Analyzed sentiment class distribution
- Reviewed word frequency and review lengths
- Explored trends and patterns within the review dataset

---

## Model Building and Training

- Built a feedforward neural network using TensorFlow/Keras
- Tuned hyperparameters by varying:
  - Dropout rates
  - Number of training epochs

---

## Evaluation and Tuning

- Tracked training vs. validation accuracy and loss across epochs
- Evaluated predictions using confusion matrices
- Visualized model performance and overfitting behavior

---

## Key Results

- The final model performed well in binary sentiment classification
- Dropout regularization improved generalization
- Demonstrated the applicability of neural networks for basic NLP tasks

---

## Applications

This pipeline can be extended for use in:
- Movie or product review sentiment analysis
- Customer satisfaction prediction
- Social media content classification
