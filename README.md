# SMS-Spam-Classifier
A Spam classifier that classifies SMS messages as spam or legitimate (ham).

# Overview
This project is designed to classify SMS messages as spam or not spam using natural language processing techniques. It uses Multinomial Naive Bayes as the classifier and TF-IDF for feature extraction. A web application has also been created to provide a simple user interface where users can input SMS text and receive real-time classification results.

# Technologies used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Streamlit (for web application)

# Dataset
The dataset used for this project consists of SMS messages labeled as spam or non-spam. It contains approximately 5,000 messages, where 13% are spam. The dataset is publicly available at Kaggle.

# Model
- **Multinomial Naive Bayes**: Chosen due to its efficiency and effectiveness in text classification problems.
- **TF-IDF Vectorization**: Used to transform the text into numerical features, giving more importance to less frequent but significant words.

# Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/nishant-1110/sms-spam-classifier.git
pip install -r requirements.txt
write the command -> streamlit run app.py

After running the project, enter an SMS message and click predict to see whether it is classified as spam or not.

The web application is built using streamlit. It provides a simple user interface for real-time classification of SMS messages.
The classifier achieved 97% accuracy and almost 100% precision on the test set.
