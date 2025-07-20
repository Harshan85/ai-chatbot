# 🤖 AI Chatbot Using Python and Machine Learning

This is a simple AI-powered chatbot built using **Python**, **Natural Language Processing (NLP)**, and **Machine Learning (ML)** techniques. The chatbot uses **TF-IDF vectorization** and **cosine similarity** to understand user queries and respond with the most relevant answers from a predefined knowledge base.

---

## 📌 Features

- Text-based conversation with intelligent response generation
- ML-based logic using TF-IDF + cosine similarity
- Works completely offline using free and open-source Python libraries
- Expandable knowledge base (easy to add more Q&A)
- Built and tested in **PyCharm**

---

## 🧠 How It Works

1. The chatbot stores a set of predefined question-answer pairs.
2. It converts the questions into vector form using TF-IDF.
3. When a user asks something, it finds the most similar question using **cosine similarity**.
4. The bot returns the corresponding response if similarity is above a threshold, else a fallback reply.

---

## 🛠️ Technologies Used

- Python 3.x
- [NLTK](https://www.nltk.org/) – for tokenization and text processing
- [scikit-learn](https://scikit-learn.org/) – for TF-IDF and cosine similarity

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-chatbot-ml.git
cd ai-chatbot-ml

