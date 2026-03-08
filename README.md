# CrediBERT – Intelligent Fake News Detection System

Google Colab file link : https://colab.research.google.com/drive/1IgrdjB7-fZ6A4TZztxYE99hSFaza0XS9?usp=sharing


CrediBERT is an AI-powered fake news detection and credibility analysis system that uses Natural Language Processing (NLP) and Machine Learning to classify news articles as real or fake.

The system leverages BERT (Bidirectional Encoder Representations from Transformers) for deep semantic understanding of text and integrates it with a Random Forest classifier for efficient and accurate classification.

The model was trained on the WELFake dataset and achieved an accuracy of 93.5%.

---

# Problem Statement

The rapid spread of misinformation and fake news on digital platforms has become a major societal challenge. Manual verification cannot keep up with the speed and scale of online information flow.

CrediBERT aims to automatically detect fake news articles in real time using advanced NLP and machine learning techniques.

---

# Key Features

• Real-time fake news detection  
• Transformer-based text understanding using BERT  
• Hybrid architecture combining deep learning and traditional ML  
• Credibility analysis of news articles  
• High classification accuracy (93.5%)  

---

# Tech Stack

Python  
BERT (Transformers)  
Scikit-Learn  
Random Forest Classifier  
Natural Language Processing (NLP)  
Pandas  
NumPy  

---

# Dataset

The model is trained on the **WELFake Dataset**, which contains a mixture of real and fake news articles collected from multiple sources.

---

# System Architecture

News Article Input  
↓  
Text Preprocessing  
↓  
BERT Embedding Generation  
↓  
Random Forest Classification  
↓  
Fake / Real Prediction  
↓  
Credibility Analysis  

---

# Model Performance

Accuracy: **93.5%**

The hybrid architecture of BERT embeddings with Random Forest classifier improves classification performance compared to traditional machine learning approaches.

---

# Installation

Clone the repository

```
git clone https://github.com/yourusername/credibert.git
```

Navigate to the project directory

```
cd credibert
```

Install dependencies

```
pip install -r requirements.txt
```

Run the model

```
python main.py
```

---

# Applications

Fake news detection platforms  
Social media monitoring systems  
Journalism verification tools  
Content credibility analysis systems  

---

# Future Improvements

Integration with live news APIs  
Explainable AI for model interpretability  
Multilingual fake news detection  
Real-time browser extensions  

---

# Authors  
Harman Saini  


Symbiosis Institute of Technology, Nagpur  
B.Tech Computer Science Engineering
