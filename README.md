# Automatic-Text-Summarization-System-
Automatic Text Summarization System

This repository contains the implementation of an **Automatic Text Summarization System** developed for the **BUAN6342 - Individual Project**. The goal of this project is to assist a committee member in summarizing daily news headlines for morning meetings by identifying the ten most important stories of the day using NLP techniques. Two major NLP libraries – **NLTK** and **spaCy** – are used and compared for their effectiveness in preprocessing and summarization.

---

## 📁 Project Structure

- headlines.csv 
- summarization_project.ipynb
- README.md

---

## 📌 Objectives

- Perform text preprocessing using **NLTK** and **spaCy**
- Apply POS tagging and Named Entity Recognition (NER)
- Vectorize text using **CountVectorizer** and **TF-IDF**
- Classify and summarize news headlines using **TextRank**
- Compare the summarization results between **NLTK** and **spaCy**
- Visualize outputs using **matplotlib**
- Deliver insights via a PowerPoint presentation

---

## ⚙️ Technologies Used

- Python 3.x
- Jupyter Notebook
- **NLTK**
- **spaCy**
- **Scikit-learn**
- **Matplotlib**
- **Pandas**

---

## 📊 Summary Flow

### Part 1 – NLTK
1. Load dataset with Pandas
2. Preprocess headlines: tokenization, stop word removal, stemming, lemmatization
3. Apply POS tagging and NER using NLTK
4. Use CountVectorizer and TF-IDF for vectorization
5. Generate summary using TextRank or alternative technique
6. Visualize and extract top 10 key headlines

### Part 2 – spaCy & Scikit-learn
1. Load and preprocess using spaCy
2. Apply spaCy’s POS tagging and NER
3. Use spaCy pipeline for efficient processing
4. Classify using TF-IDF and LinearSVC in Scikit-learn pipeline
5. Summarize using TextRank
6. Visualize and extract top 10 headlines

---

## 📷 Output Comparison

At the end of the notebook:
- Two grids display top 10 headline summaries side-by-side:
  - **Left**: NLTK results
  - **Right**: spaCy results

---

## 📽 Presentation Overview

1. Importance of preprocessing, POS, and NER
2. Workflow flowcharts for both methods
3. Visual summary comparison
4. Final conclusion on performance and efficiency

---

## ✅ Conclusion Options

You may draw one of the following based on the analysis:
- NLTK is slightly more efficient
- spaCy outperforms NLTK
- Both libraries are effective, and choice depends on project needs

---

## 🏆 Project Highlights

- End-to-end NLP pipeline for summarizing real-world news data
- Comparison of top NLP libraries: NLTK vs spaCy
- Visual storytelling through summary and PowerPoint presentation

---

## 📬 Contact

For any questions or suggestions, feel free to open an issue or connect via email.

---


**Author:** Ashlesha Sanjay Kadam

