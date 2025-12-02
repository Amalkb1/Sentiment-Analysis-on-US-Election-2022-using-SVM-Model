# Sentiment-Analysis-on-US-Election-2022-using-SVM-Model
Completed a project on Sentiment Analysis of US Election 2022 using SVM. Collected and cleaned Twitter data, applied TF-IDF, and built an SVM model that achieved 91% accuracy in classifying tweets as positive, negative, or neutral. Excited to explore more ML + NLP projects and real-world applications.
📌 Overview

Millions of tweets were shared during the election period, making manual analysis impossible. This project automates the process by:

🔹 Collecting and preprocessing Twitter data
🔹 Converting text into numerical form using TF-IDF
🔹 Training a Linear SVM classifier
🔹 Evaluating model performance using accuracy, precision, recall, and F1-score
🔹 Visualizing sentiment trends and comparisons between candidates

The trained model achieved 91% accuracy, proving high efficiency in sentiment classification.

🧠 Features

✔ Sentiment detection (Positive / Negative / Neutral)
✔ NLP-based text cleaning (stopwords, lemmatization, special characters removal)
✔ TF-IDF feature extraction
✔ SVM model training and testing
✔ Visualizations — Word Cloud, Confusion Matrix, Sentiment Distribution
✔ Candidate-wise sentiment comparison (Trump vs Biden)

🛠️ Tech Stack
Category	Tools
Language	Python
Libraries	pandas, numpy, nltk, scikit-learn, matplotlib, seaborn, plotly, textblob
ML Algorithm	Support Vector Machine (LinearSVC)
Environment	Jupyter Notebook / Google Colab
📂 Folder Structure
├─ dataset/
│   ├─ hashtag_donaldtrump.csv
│   ├─ hashtag_joebiden.csv
├─ src/
│   ├─ preprocessing.py
│   ├─ training.py
│   ├─ visualization.py
├─ sentiment_analysis_US_Election.ipynb
├─ requirements.txt
└─ README.md


▶️ Usage
jupyter notebook sentiment_analysis_US_Election.ipynb


Modify input text to predict sentiment:

model.predict(tfidf.transform(["your tweet here"]))

📊 Results
Metric	Score
Accuracy	91%
Model	LinearSVC
Dataset	US Election tweets

The analysis showed clear sentiment patterns and revealed which candidate received more positive responses based on the dataset.

📌 Visual Outputs

🔹 Word Cloud
🔹 Confusion Matrix
🔹 Sentiment Bar Graph
🔹 Trump vs Biden sentiment comparison

(Upload images and add them here later)

🔮 Future Enhancements

🚀 Real-time sentiment analysis using Twitter API
🤖 Deep learning models (LSTM / BERT)
📊 Interactive dashboard using Streamlit / Power BI
🌍 Multilingual sentiment support
📌 Topic-based sentiment categorization

🤝 Contributing

Contributions are welcome!
Feel free to submit a pull request or open an issue.

👤 Author

Amal K B
B.Sc. Data Science & Analytics
📬 Open to ML/NLP projects, internships & collaborations
