[←🏠 Back to Main Portfolio Hub](https://github.com/BrandonLee-98/AI-Portfolio-Brandon-Matias)

# 📰 Natural Language Processing: Coursework Collection
**ITAI 2373 | Houston City College** | **Brandon Matias**

This repository serves as a comprehensive collection of my work in Natural Language Processing (NLP). It documents my journey from understanding basic text cleaning to building a fully automated, machine-learning-driven news classification system. 

As an **Aspiring AI Developer**, this coursework has allowed me to explore how we can use Python to help computers understand, interpret, and respond to human language in meaningful ways.

---
#### 📰 NLP: Full Coursework Collection
* **[NewsBot 2.0 Capstone](https://github.com/BrandonLee-98/ITAI2373-NewsBot-Final)** : My most advanced project—an automated news aggregator with sentiment analysis and SMOTE data balancing.
* **[Midterm Project](https://github.com/BrandonLee-98/ITAI2373-Midterm-Project)** : The foundational logic for the NewsBot system.
* **[NLP Labs](https://github.com/BrandonLee-98/Brandon-Matias-NLP-ITAI2373/tree/2ff4e0d4ba32b355021056cd245e326c454ff079/NLP%20Labs)** : Individual modules covering tokenization, POS tagging, and vectorization.
---
### 📊 Master Coursework Table

I have organized my assignments to show the progression of skills required to build complex AI systems.

| Assignment | Topic | Key Skills & Learning Outcomes |
| :--- | :--- | :--- |
| **Lab 02** | NLP Processing Techniques | Mastered text "normalization" including tokenization, lemmatization, and removing stop words. |
| **Lab 04** | Text Representation | Explored Vectorization (TF-IDF) to convert raw text into numerical data for machine learning models. |
| **Lab 05** | Part-of-Speech Tagging | Used NLTK to identify parts of speech (nouns, verbs, etc.) to understand sentence structure. |
| **Lab 07** | Sentiment & Emotion Analysis | Implemented models to classify the emotional "tone" of text data. |
| **Midterm** | NewsBot Intelligence System | Collaborative project building a basic news scraper and classification pipeline. |
| **Capstone** | **NewsBot 2.0 (Final Project)** | A complete end-to-end system for news aggregation and sentiment classification. |

---

## 🚀 Featured Project: NewsBot Intelligence System 2.0

### The Capstone Project
### 🧩 Problem Statement

In today's global market, organizations and analysts are overwhelmed by "information fatigue." It is no longer cost-effective to manually sort through thousands of daily articles to find actionable intelligence. Furthermore, decision-makers constantly hit the "Language Wall"—with a massive portion of critical global news originating in non-English markets. Legacy systems miss these signals, causing delays in competitive response and market strategy.

### 🛠️ Methodology & Approach

For this system, I transitioned from foundational NLP scripts into building a production-ready, modular intelligence pipeline that:
* **Analyzes Content Dynamically:** Implements Zero-Shot Classification (`distilbart-mnli`) to categorize news on the fly without pre-defined training labels, alongside Latent Dirichlet Allocation (LDA) to discover hidden statistical themes.
* **Synthesizes Intelligence:** Generates abstractive, human-like executive summaries using a dedicated `distilbart-cnn` transformer model, reducing reading load by 90%.
* **Breaks the Language Barrier:** Uses a multilingual pivot architecture to automatically detect and translate global news (e.g., Spanish, French, German) into English for uniform pipeline processing.
* **Interrogates Data:** Features an extractive Question Answering (QA) chatbot (`minilm-uncased-squad2`) integrated into a custom Flask web dashboard, allowing users to "interview" the article context directly.

### 💡 Learning Outcomes

Through this project, I realized that **modular architecture is not a luxury; it is a survival mechanism.** Transitioning from experimental Jupyter notebooks to a production-ready, service-oriented application forced me to confront real-world engineering challenges, such as "dependency hell" involving legacy library locks and binary mismatches. I learned that strictly decoupling my NLP modules—separating the translation logic from the summarization engine, for example—ensured the system remained scalable and robust against individual component failures. 

### 🛠️ Technical Arsenal

These are the specific tools and libraries I practiced with to build this full-stack NLP platform:
* **Hugging Face Transformers:** For implementing state-of-the-art zero-shot classification, abstractive summarization, and extractive QA models.
* **Scikit-Learn & Pandas:** For building the statistical topic modeling (LDA) pipeline and handling complex data manipulation.
* **Flask & Chart.js:** For developing the interactive Single Page Application (SPA) dashboard and rendering real-time sentiment evolution visualizations.
* **Deep-Translator & Langdetect:** For executing the cross-lingual analysis and automated translation workflows.

---
### 🔗 Portfolio Navigation
* 🏠 Back to [Main Portfolio Hub](https://github.com/BrandonLee-98/AI-Portfolio-Brandon-Matias)
* 📧 Contact: bmatias98@outlook.com
