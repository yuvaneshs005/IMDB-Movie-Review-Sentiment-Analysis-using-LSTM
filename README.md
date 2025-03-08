# IMDB Movie Review Sentiment Analysis using LSTM
This project aims to build a Sentiment Analysis Model for movie reviews using the IMDB dataset. The model classifies reviews as either positive or negative using Natural Language Processing (NLP) and Deep Learning (LSTM) techniques. The dataset is sourced from Kaggle (lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), and the project follows a structured approach, including data preprocessing, model training, evaluation, and prediction.

# 🚀 Project Workflow

1️⃣ Data Collection

Downloaded the dataset from Kaggle.

Loaded the dataset into a Pandas DataFrame for processing.

2️⃣ Data Preprocessing

Tokenization and padding of text data.

Splitting dataset into training (80%) and testing (20%) sets.

3️⃣ Model Building

Used an LSTM (Long Short-Term Memory) architecture for sentiment classification.

The model consists of an Embedding Layer, LSTM Layer, and Dense Output Layer.

4️⃣ Model Training & Evaluation

Epochs: 5

Test Accuracy: 88.3%

Test Loss: 0.3139

5️⃣ Predictive System

Developed a function to predict the sentiment of a given review.

# 🤖 Technologies Used

Python

TensorFlow/Keras

Scikit-learn

Pandas & NumPy

Natural Language Processing (NLP)

# Results
Test Accuracy: 88.3%

Test Loss: 0.3139

The model was evaluated using binary cross-entropy loss and accuracy metrics. The test accuracy of 88.3% indicates that the model performs well in classifying movie reviews into positive and negative sentiments.

# 📌 Installation & Usage

🔹 Prerequisites

Ensure you have the following libraries installed:

pandas

tensorflow

scikit-learn
