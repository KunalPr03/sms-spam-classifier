# 📩 SMS Spam Classifier

A Machine Learning project that classifies SMS and email messages as **Spam** or **Not Spam** using Natural Language Processing (NLP).

## 🚀 Live Demo

[Open the Live Application](https://sms-spam-classifier-kunal.streamlit.app/)

## 📌 Project Overview

This project uses Natural Language Processing and Machine Learning to automatically detect whether a given message is spam.

The application provides a simple Streamlit interface where users can enter a message and receive a prediction.

## 🛠️ Technologies Used

- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Streamlit
- TF-IDF Vectorization
- Multinomial Naive Bayes

## 🔄 Machine Learning Pipeline

```text
SMS / Email Message
        ↓
Text Preprocessing
        ↓
Tokenization
        ↓
Stopword Removal
        ↓
Stemming
        ↓
TF-IDF Vectorization
        ↓
Multinomial Naive Bayes
        ↓
Spam / Not Spam
```

## 📂 Project Structure

```text
sms-spam-classifier/
│
├── app.py
├── main.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## ▶️ Run Locally

Clone the repository:

```bash
git clone https://github.com/KunalPr03/sms-spam-classifier.git
```

Go into the project:

```bash
cd sms-spam-classifier
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

## 🧠 Model

The project uses:

- **TF-IDF** for converting text into numerical features.
- **Multinomial Naive Bayes** for spam classification.
- **NLTK** for text preprocessing.

## 💡 Example

### Spam

```text
Congratulations! You have won a free iPhone. Click now to claim your prize!
```

**Prediction:** Spam Detected

### Not Spam

```text
Hey, are we still meeting today at 5 PM?
```

**Prediction:** Not Spam Detected

## 🌐 Deployment

The application is deployed using Streamlit Community Cloud.

**Live Demo:**  
https://sms-spam-classifier-kunal.streamlit.app/

## 👨‍💻 Author

**Kunal Prajapat**

GitHub: https://github.com/KunalPr03