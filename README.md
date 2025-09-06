A machine learning-powered Fake News Detection system that leverages NLP techniques and Logistic Regression to classify news as real or fake. Text is preprocessed with stemming, stopword removal, and TF-IDF vectorization. A Streamlit web app enables real-time predictions, making it an interactive tool to fight misinformation.

Project Structure

-app.py : Streamlit app for interactive fake news detection

-fake news.py : Data loading and inspection script

-train.csv : Dataset containing news articles with labels

Features

-Fake News Classification using Logistic Regression

-Text Preprocessing with stemming and stopword removal

-TF-IDF Vectorization for feature extraction

-Train/Test Split with accuracy evaluation

-Streamlit Web App for real-time predictions

Technologies Used

-Programming Language: Python

-Libraries: Pandas, NumPy, Scikit-learn, NLTK, Streamlit

-Machine Learning Model: Logistic Regression

-Dataset: train.csv (news articles with labels: 1 = Fake, 0 = Real)

Getting Started
Prerequisites: Install required Python libraries:
pip install pandas numpy scikit-learn nltk streamlit

Run the Streamlit App:
streamlit run app.py

This will open the interactive web app in your browser.

Preview

Input Field: Enter a news article or headline.

Output: Displays whether the news is Real or Fake.

Future Improvements

-Add deep learning models (e.g., LSTM, BERT) for improved accuracy

-Expand dataset with more diverse sources

-Deploy app on Heroku/Streamlit Cloud for public use

-Provide confidence scores along with predictions
