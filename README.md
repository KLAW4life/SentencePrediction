# SentencePrediction

This is my introductory personal project into learning AI with sentence prediction.

Description:

This repository implements a word prediction model that can predict the next word in a sequence for both English and Spanish languages. It utilizes the pre-trained BERT model (bert-base-multilingual-cased) for multilingual word prediction.

Features:

Supports English and Spanish language prediction
Utilizes BERT for next-word prediction
Provides training and evaluation functionalities

Requirements:

Python 3.x
PyTorch
Transformers library
pandas
nltk

Usage:

Clone the repository.
Install required dependencies using pip install -r requirements.txt.
Upload your English-Spanish bilingual CSV file containing sentences in the "data" folder (create one if it doesn't exist).
Run the script to train and evaluate the model.

Evaluation:

The script prints the accuracy score on the English and Spanish test datasets after training.

Further Development:

Experiment with different hyperparameters (learning rate, epochs)
Explore fine-tuning the pre-trained BERT model for better performance
Implement a user interface for interactive word prediction

