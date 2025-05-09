# Tweet Processor

Tweet Processor is a Python-based application that processes and classifies tweets into positive and negative categories using sentiment analysis techniques. The project leverages a custom processing pipeline to clean, analyze, and categorize tweet data.

---

## 📌 Features

* **Sentiment Analysis:** Classifies tweets into `positive` and `negative` categories.
* **Data Preprocessing:** Cleans tweets by removing stopwords and special characters.
* **JSON Data Handling:** Reads from `positive_tweets.json` and `negative_tweets.json` for input.
* **Stopwords Filtering:** Utilizes `english_stopwords.txt` for preprocessing.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed:

```bash
sudo apt-get update
sudo apt-get install python3
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Dependencies:

* `nltk`
* `numpy`

---

## 📂 Directory Structure

```
.
├── tweet_processor.py       # Main application logic
├── requirements.txt         # List of dependencies
├── positive_tweets.json     # Dataset of positive tweets
├── negative_tweets.json     # Dataset of negative tweets
└── english_stopwords.txt    # Stopwords list for preprocessing
```

---

## 💡 Usage

Run the tweet processor script:

```bash
python3 tweet_processor.py
```

---

### Example:

```plaintext
Input: "I love sunny days!"
Output: "Positive"

Input: "I hate waiting in traffic."
Output: "Negative"
```

---

## 🤝 Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.
