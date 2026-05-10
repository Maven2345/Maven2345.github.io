import pandas as pd
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.naive_bayes import PassiveAggressiveClassifier
from sklearn.model_selection import train_test_split

# Load dataset and clean text
def train_news_detector(data_path):
    df = pd.read_csv(data_path)
    labels = df.label

    # Split the dataset
    x_train, x_test, y_train, y_test = train_test_split(df['text'], labels, test_size=0.2)

    # Initialize TfidfVectorizer to analyze word frequency patterns
    tfidf_vectorizer = TfidfVectorizer(stop_words='english', max_df=0.7)
    tfidf_train = tfidf_vectorizer.fit_transform(x_train) 

    # Initialize a PassiveAggressiveClassifier (Excellent for high-volume text)
    pac = PassiveAggressiveClassifier(max_iter=50)
    pac.fit(tfidf_train, y_train)
    
    print("Classifier successfully trained for misinformation detection.")
