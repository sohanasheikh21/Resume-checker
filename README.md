# 📄 Resume Checker – JD-Based ATS Analyzer

**Resume Checker** is an AI-powered tool that evaluates resumes against job descriptions (JDs) using Optical Character Recognition (OCR), Natural Language Processing (NLP), and a skill-matching algorithm. This project provides an ATS (Applicant Tracking System) match score and intelligent role suggestions to improve job application success rates.

## 🚀 Features

- 🧠 **Skill Matching:** Compares resume content with a wide array of predefined job role skills.
- 📊 **ATS Score Visualization:** Displays match percentage using an informative pie chart.
- 🔍 **Job Fit Analysis:** Suggests the best matching role(s) with skill overlap scores.
- 📝 **Keyword Extraction:** Analyzes the JD to identify relevant keywords.
- 🌐 **Gradio Interface:** Simple web-based UI for uploading resumes and inputting JDs.

## 🛠️ Built With

- Python
- Gradio
- Tesseract OCR & pdf2image
- NLTK
- Matplotlib
- PyMuPDF (fitz)

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
