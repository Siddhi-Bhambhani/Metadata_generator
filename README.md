## Automated Metadata Generation System

This project delivers a smart, scalable solution for automatically generating metadata from unstructured documents.  
It enhances document discoverability, classification, and analysis by extracting key information and presenting it in a structured format.  
The system includes a user-friendly web interface built with Streamlit.

---

## Key Features

- Automated metadata generation for various file types (PDF, DOCX, TXT)
- Text extraction with built-in OCR for scanned documents
- Semantic content analysis using NLP techniques
- Structured metadata output, including:
  - Title
  - Summary
  - Keywords
  - Named Entities
  - Content length
- Interactive web interface for document upload and metadata viewing

---

## Project Structure

- `app.py` – Streamlit web interface  
- `metadata_utils.py` – Text extraction, OCR, and NLP logic  
- `requirements.txt` – Python dependencies  
- `runtime.txt` – Python version configuration for deployment  
- `sample_files/` – Test documents (optional)

---

## How It Works

1. Users upload a document through the web interface.  
2. The system extracts the text, applying OCR if needed.  
3. It processes the content to identify key phrases, named entities, and summaries.  
4. Metadata is presented instantly in a clean, structured format.

---

## Deployment

The app can be deployed using Streamlit.  
Simply push the project to a GitHub repository and connect it to Streamlit for seamless access from anywhere.

---

## Technologies Used

- Python  
- Streamlit  
- spaCy  
- NLTK  
- RAKE (Rapid Automatic Keyword Extraction)  
- PyMuPDF  
- pdf2image + Tesseract OCR  
- python-docx  

---

## Demo

A short demo video (approx. 5 minutes) showcases the metadata extraction process via the web interface.  
Zip file been uploaded
