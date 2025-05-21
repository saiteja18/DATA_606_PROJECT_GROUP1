# VeriNews AI – Detect. Summarize. Translate.

A comprehensive NLP-powered application for Fake News Detection using traditional machine learning and transformer-based models. This project also features real-time news summarization, translation, and question answering – all packaged within a modular Streamlit application.

---

## 📌 Project Overview

This project was developed as part of the DATA 606 Capstone at UMBC. It aims to tackle misinformation by classifying news articles as real or fake, while also empowering users to better understand the content through summarization, translation, and Q&A.

**Core Features:**
- Fake News Classification using Logistic Regression, SVM, Random Forest, and fine-tuned BERT
- Abstractive Text Summarization using BART
- Translation of news and summaries using Google Translate API
- Question Answering based on article content using DistilBERT
- Streamlit-based interactive frontend

---

## 📂 Repository Structure

```bash
.
├── Modeling_Python_Scripts/
│   ├── BERT_Fake_News_Detection.ipynb
│   ├── FINAL_FINE_TUNING_BERT_CLASSIFICATION_FAKE_NEWS.ipynb
│   ├── Fake_News_Detection_Using_NLP.ipynb
│   ├── EDA_News_Articles.ipynb
│   ├── streamlit_news_classification_abstractive_text_summarization_runner.ipynb
│   └── verinews_app.ipynb
│
├── News_Articles_Scraping_Scripts/
│   ├── getCnnNews.ipynb
│   ├── getFoxNews.ipynb
│   ├── getAbcNews.ipynb
│   ├── getNewsTechcrunch.ipynb
│   ├── getDataNewsApi.ipynb
│   ├── getFullArticlesCnn.ipynb
│   ├── getNewsUrlsFoxNews.ipynb
│   ├── getNewsUrlsFromTechcrunch.ipynb
│   └── getNewsFromNewsApi.ipynb
│
├── README.md
