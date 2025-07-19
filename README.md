# 📄 Resume Analyzer with ATS Score & Role Recommendation

This project is an **AI-powered Resume Analyzer** that matches resumes against job descriptions (JD) using OCR, NLP, and skill matching techniques. It calculates the **ATS (Applicant Tracking System) match score**, recommends the most suitable job roles, and provides suggestions for improvement.

---

## 🚀 Features

- 🔍 Extracts text from PDF resumes using OCR (`pytesseract` and `pdf2image`)
- 📑 Matches resume content with job descriptions using NLP
- 💡 Identifies and highlights relevant skills
- 🎯 Suggests best-fit job roles from a predefined list (AI/ML, Data Analyst, Web Developer, etc.)
- 📊 Displays ATS match score as a pie chart
- 🌐 Simple and interactive Gradio web interface

---

## 🛠️ Technologies Used

- Python
- Gradio (Web UI)
- PyMuPDF (`fitz`) for PDF parsing
- pytesseract for OCR
- pdf2image
- NLTK for text processing
- matplotlib for visualizations

---

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
