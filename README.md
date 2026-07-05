# AI-Powered Semantic Research Paper Retrieval System

## Overview

This project is an AI-powered semantic research paper retrieval system developed using Natural Language Processing (NLP) and Machine Learning techniques. It helps users find the most relevant research papers based on the meaning of their search query rather than simple keyword matching.

The system uses Sentence Transformers to generate semantic embeddings, FAISS for fast similarity search, and several NLP techniques such as text summarization, keyword extraction, named entity recognition, and topic modeling to provide meaningful insights from retrieved research papers.

---

## Features

- Semantic search using Sentence Transformers
- Fast similarity search with FAISS
- Automatic research paper summarization
- Keyword extraction using KeyBERT
- Named Entity Recognition (NER) using spaCy
- Topic modeling using BERTopic
- Precision@K evaluation of retrieval performance

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- KeyBERT
- spaCy
- BERTopic
- Scikit-learn
- Matplotlib

---

## Project Workflow

1. Load the research paper dataset.
2. Preprocess and clean the text.
3. Generate semantic embeddings using Sentence Transformers.
4. Store embeddings for efficient retrieval.
5. Retrieve the most relevant papers using semantic similarity.
6. Generate summaries of retrieved papers.
7. Extract important keywords.
8. Identify named entities.
9. Perform topic modeling.
10. Evaluate retrieval performance using Precision@K.

---

## Dataset

This project uses the ML-ArXiv Papers dataset from Hugging Face, containing research papers from various machine learning domains.

---

## Running the Project

1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Mount Google Drive when prompted.
4. Download the embeddings file from the link provided below.
5. Place the file in the root directory of your Google Drive (`MyDrive`).
6. Run all notebook cells.

---

## Embeddings File

The embeddings file is not included in this repository because it exceeds GitHub's file size limit.

Download the embeddings file from:

**Google Drive:**  
*(https://drive.google.com/file/d/14d9B3Q30QShcSz4cD7JgBxgcJkJRRmeu/view?usp=sharing)*

Place the downloaded file in:

```
MyDrive/arxiv_embeddings.npz
```

before running the notebook.

---

## Repository Structure

```
├── CBSOT_PROJECT_final9.ipynb
├── README.md
├── requirements.txt
```

---

## Future Improvements

- Web-based user interface
- Real-time research paper retrieval
- Multi-dataset support
- Citation and reference analysis
- Personalized paper recommendations

---

## Author

**Shrena Bansal**
