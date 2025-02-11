# LANGUAGE-DETECTION

Overview
This project implements a machine learning and NLP-based language detection system using the Naïve Bayes algorithm. Users can input a text in different languages, and the model predicts the language, similar to Google Translator. The project aims to assist in solving language translation problems.

Dataset
The dataset used for training the model is stored in Language Detection.csv. It contains text samples in various languages, with their corresponding language labels.

Sample Data

Text                          Language

Bonjour tout le monde         French

Hola, ¿cómo estás?            Spanish

Hello, how are you            English

Guten Morgen                  German

Ciao, come stai?              Italian

Dependencies

Ensure you have the following libraries installed before running the script:
pip install pandas numpy scikit-learn

Implementation

The project follows these steps:

Load the dataset using Pandas.

Preprocess the data by extracting text and language labels.

Convert text data into numerical features using CountVectorizer.

Split the dataset into training and testing sets.

Train a Naïve Bayes classifier (MultinomialNB) on the training data.

Evaluate the model's accuracy on the test set.

Accept user input and predict the language of the entered text.

Usage

Clone the repository:
git clone https://github.com/your-username/language-detection.git

Navigate to the project directory:
cd language-detection

Install dependencies:
pip install pandas numpy scikit-learn

Run the script:
python language_detection.py

Enter a text sample when prompted, and the model will predict the language.

Results

The model achieves a high accuracy in detecting different languages. The accuracy may vary depending on the dataset size and language diversity.

Future Improvements

Expand the dataset to include more languages.

Implement deep learning models for improved accuracy.

Develop a web or mobile interface for real-time language detection.





