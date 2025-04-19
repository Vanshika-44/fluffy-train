# Fake News Detection using Machine Learning and Data Science Techniques

This project demonstrates the application of machine learning and Natural Language Processing (NLP) techniques to classify news articles as either real or fake. The objective of this project is to develop an automated system that can analyze textual data and identify the authenticity of news content.

## Project Overview

This project leverages a dataset of news articles and applies various preprocessing steps, such as tokenization and vectorization, to convert the text data into a format suitable for machine learning algorithms. Several classification algorithms, including Logistic Regression, Decision Trees, and Random Forest, are employed to train a model capable of distinguishing between real and fake news.

### Key Features:
- *Text Preprocessing*: Includes cleaning, tokenization, and vectorization of news article text.
- *Model Training*: Implementation of multiple machine learning models to evaluate and predict the authenticity of news.
- *Evaluation Metrics*: Accuracy, precision, recall, and F1-score are used to evaluate the performance of the models.

## Installation

To run this project, you'll need the following dependencies:

- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn

You can install the required libraries by running the following command:

pip install -r requirements.txt

## USAGE
1.Clone the Repository: Clone this repository to your local machine using Git:
  git clone https://github.com/Vanshika-44/fluffy-train.git
  
2. Install Dependencies: After cloning the repository, navigate to the project directory and install the necessary libraries:

 pip install -r requirements.txt

3. Run the Jupyter Notebook: Open the fake_news_detection.ipynb notebook to explore the data,train the models,and make predictions on new articles.
   To start the Jupyter Notebook make the following command:
   jupyter notebook
   
4. Model Prediction: After training the model,use it to predict whether a given news article is real or fake baed on its content.
