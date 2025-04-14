# 🛍️ Automated Customer Reviews – Sentiment Analysis & Smart Summarization

In today's digital world, customer reviews are everywhere. But with the overwhelming number of opinions online, it's challenging to keep up and extract meaningful insights.

This project uses **Natural Language Processing (NLP)** and **Generative AI** to:
- 🟢 Classify customer reviews by sentiment
- 🧩 Cluster products into categories
- 📝 Summarize reviews into clear recommendation articles


---

## 📂 Datasets

Used two Amazon review datasets containing product ratings and customer feedback.

---

## 🧠 Sentiment Classification

- Model: **RoBERTa (roberta-base)**
- Trained using PyTorch with accuracy, precision, recall, and F1-score as evaluation metrics
- with 95% accuracy,f1 score 
---

## 🧩 Product Clustering

- Embeddings via **all-mpnet-base-v2**
- Applied **KMeans** to group products into 6 themes
- Visualized using **UMAP**

---

## 📰 Review Summarization

Used **GPT-4** to:
- Highlight top-rated and worst-rated products
- Summarize common customer feedback

---

## 📌 Tech Stack

- Python, PyTorch, Transformers (HuggingFace)
- KMeans, UMAP
- GPT-4 (OpenAI API)
- Streamlit

---

## 🙌 Credits

Built with ❤️ using real-world Amazon reviews and the latest in AI.
