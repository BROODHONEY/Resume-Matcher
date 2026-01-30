# AI-Powered Resume Matcher using BERT

A beginner-friendly project that uses Machine Learning and NLP to match resumes to job descriptions based on **semantic similarity**. Built in a Jupyter Notebook for learning purposes.

---

## Project Overview

This project extracts text from real resumes (PDF/DOCX) stored inside the `resumes/` folder, embeds them using **Sentence-BERT**, and matches them against a job description using **cosine similarity**. The goal is to simulate how modern ATS (Applicant Tracking Systems) work, and to learn about **semantic text similarity**, **text embedding**, and **NLP in ML applications**.

---

## Features

- Parse resumes in **PDF and DOCX** formats
- Extract and clean resume text
- Embed resumes and job descriptions using **Sentence-BERT**
- Calculate semantic similarity with **cosine similarity**
- Rank resumes based on relevance to the job description
- Interactive Jupyter Notebook-based exploration

---

## Tech Stack

- **Python 3**
- **Jupyter Notebook**
- **Sentence-Transformers (BERT Embeddings)**
- **scikit-learn** (for cosine similarity)
- **pdfplumber** (for PDF parsing)
- **docx2txt** (for DOCX parsing)

---

## Try It Yourself

- **Clone the repository**
  ```bash
  git clone https://github.com/BROODHONEY/Resume-Matcher.git
  cd Resume-Matcher
  ```
- **Install requirements**
  Install the required libraries from the `requirements.txt`
- **Import your resume and update the job description**
  Store your resumes inside the `resumes/` folder and update the `job_description` inside the notebook.

---

## Author
Roshan R P
B.Tech AIML Student | Aspiring ML Engineer
📧 rproshan11@gmail.com
