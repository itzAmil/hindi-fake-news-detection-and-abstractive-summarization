# 📰  Hindi Fake News Detection and Abstractive Summarization

This project integrates **Fake News Detection**, **Explainability**, and **Abstractive Summarization** for **Hindi news articles**.

It uses **BERT** model to classify news as real or fake, explains its predictions using **LIME**, and generates a summary of the news article using the **T5 model** — all in one seamless pipeline.

---

## 🚀 Features

-  Fake News Detection using fine-tuned **BERT**
-  Real-time prediction: Real or Fake
-  Model Explainability using **LIME**
-  Abstractive Summarization using **T5 Transformer**
-  Streamlit-based interactive UI
-  Supports Hindi language inputs 

---

## 🧠 Model Architecture

|         Task           |     Model      |
|------------------------|----------------|
| Classification         | BERT           |
| Explainability         | LIME           |
| Summarization          | T5 Transformer |

---

## 📁 Dataset

- **Fake News Detection**: Custom Hindi dataset (balanced) containing real/fake labels
- **Summarization**: Hindi news article samples for training/testing the T5 model
- Datasets preprocessed using NLP techniques (cleaning, tokenization)

---

## 🧰 Tech Stack

- Python 3.13
- BERT (Classification)
- scikit-learn
- LIME (Explainability)
- PyTorch
- Pandas, NumPy
- T5 (Summarization)
- Streamlit (UI)

---

## 🚦 How It Works

1. User pastes a **Hindi news article** into the Streamlit UI.
2. The article is passed to a **fine-tuned BERT model** for classification.
3. If classified as real/fake, **LIME** explains the prediction via token-level highlights.
4. In parallel, a **T5 model** generates a **concise summary** of the article.

---

## 👥 Contributors

This project was originally developed as part of a group academic project.

**Original Contributors:**
- Amil Gauri (Maintainer)  
- Vikas Pandit  
- Bhushan Salve  
- Ajay Chaurasiya  

> Project restructured, documented, and maintained by **Amil Gauri** for public release.

---

## 📄 License

This project is open-source under the MIT License.  
You are free to use, modify, and distribute it with proper credit.

See the [LICENSE] file for full details.

---

