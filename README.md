# 📘 LearnIQ Engine

### AI-Driven Personalised Learning from Academic PDFs

---

## 📌 Overview

**LearnIQ Engine** is an AI-powered personalised learning system that transforms academic PDFs into structured study notes, interactive assessments, and performance-based visual feedback.

The project addresses a real-world learning challenge faced by students: difficulty in continuously tracking understanding across multiple subjects while studying from large, unstructured PDF materials such as lecture notes and textbooks.

By applying **Natural Language Processing (NLP)** and **unsupervised learning techniques**, LearnIQ Engine bridges the gap between *passive reading* and *active self-assessment*.

---

## 🎯 Problem Statement

Students primarily rely on academic PDFs for learning, but these documents:

* Are lengthy and unstructured
* Do not highlight important topics clearly
* Do not support continuous self-evaluation
* Offer no personalised feedback

As a result, students often realise their weak areas **only after examinations**, limiting opportunities for improvement.

---

## 💡 Motivation

This project is motivated by a **real personal experience** as a B.Tech student managing multiple subjects simultaneously. Despite regular study, there was no clear way to:

* Measure understanding topic-wise
* Perform self-evaluation before exams
* Receive structured feedback from study material

LearnIQ Engine was developed to solve this exact problem using AI.

---

## 🚀 Key Features

* 📄 **Academic PDF Processing**
  Extracts and preprocesses text from lecture notes and textbooks.

* 🧠 **Important Content Identification**
  Uses TF-IDF to identify high-importance sentences.

* 🧩 **Automatic Topic Discovery**
  Groups content into topics using unsupervised clustering.

* 📘 **Structured Learning Notes**
  Separates and presents:

  * Conceptual explanations
  * Diagram/visual references
  * Code and syntax snippets

* 📝 **Interactive Mock Tests**
  Supports:

  * Multiple Choice Questions (MCQs)
  * Fill-in-the-Blank questions

* 📊 **Performance Evaluation**
  Calculates overall and topic-wise accuracy based on user responses.

* 🧠 **Personalised Feedback**
  Classifies understanding as:

  * Strong
  * Moderate
  * Weak

* 🗺️ **Visual Insights**
  Displays:

  * Accuracy graphs
  * Colour-coded personalised learning mind maps

---

## 🏗️ System Pipeline

```
Academic PDF
   ↓
Text Extraction
   ↓
Text Cleaning & Sentence Tokenisation
   ↓
TF-IDF Importance Scoring
   ↓
Automatic Topic Discovery (Clustering)
   ↓
Structured Learning Notes
   ↓
Interactive Assessment (MCQ / Fill-in-the-Blank)
   ↓
Performance Evaluation
   ↓
Personalised Feedback & Mind Map
```

---

## 🤖 AI Techniques Used

* **Natural Language Processing (NLP)**
* **TF-IDF Vectorisation** for importance scoring
* **Unsupervised Learning (K-Means Clustering)** for topic discovery
* **Rule-based Question Generation**
* **Graph-based Visualisation** using NetworkX

### Why these techniques?

* Lightweight and efficient
* Explainable and transparent
* No large labelled dataset required
* Suitable for academic text analysis

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries & Tools:**

  * Scikit-learn
  * NLTK
  * pdfplumber
  * NetworkX
  * Matplotlib
  * NumPy

---

## 🧪 How It Works (User Flow)

1. User uploads an academic PDF
2. System extracts and cleans text
3. Important concepts are identified
4. Topics are automatically discovered
5. Structured study notes are generated
6. User studies the notes
7. User selects assessment type
8. User attempts the test
9. System evaluates responses
10. Personalised feedback and visuals are generated

---

## 📊 Results & Output

* Topic-wise learning insights
* Accuracy graphs
* Colour-coded personalised mind maps
* Clear identification of weak areas

This enables **focused revision and continuous improvement**.

---

## 📈 Future Enhancements

* Additional interactive question types
  *(True/False, scenario-based questions)*
* Time-based accuracy and speed analysis
* Adaptive difficulty adjustment
* Long-term learner progress tracking
* Web or mobile application integration

---

## 🎓 Learning Outcomes

* Hands-on application of NLP on unstructured data
* Designing explainable AI systems
* Building user-centric AI solutions
* Integrating AI outputs with visual analytics
* Managing end-to-end AI pipelines

---

Just tell me 👍
