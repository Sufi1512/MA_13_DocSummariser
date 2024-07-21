# AI-Powered Multimedia Processing Web Application

## Overview

This project is a web application that utilizes AI and machine learning to process and extract information from various multimedia sources. The application provides functionalities for:

- Extracting text from images using OCR.
- Extracting and processing text from PDF files.
- Summarizing YouTube videos and local video files.
- Answering user questions based on the extracted and processed text.

## Features

1. **Image to Text (OCR)**
   - Upload images and extract text using Tesseract OCR.
   - Process the extracted text for question-answering capabilities.

2. **PDF to Text**
   - Upload PDF files and extract text.
   - Process the extracted text for question-answering capabilities.

3. **Video Summarization**
   - Summarize YouTube videos by extracting transcripts and generating concise summaries.
   - Summarize local video files by extracting audio, converting it to text, and generating summaries.

## Tech Stack

- **Backend**: Flask, Python
- **Frontend**: HTML, CSS, JavaScript
- **AI/ML**: Langchain, Google Generative AI, Tesseract OCR, PyPDF2, YouTube Transcript API, MoviePy, SpeechRecognition, Transformers

## Setup

### Prerequisites

- Python 3.8+
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```sh
   git clone Sufi1512/MA_13_DocSummariser    
   cd MA_13_DocSummariser   
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate
3. Install the required packages:  
   ```shh
   pip install -r requirements.txt


4. Set up environment variables:
  . Create a .env file in the root directory.
  . Add your Google API key
   ```shh
   GOOGLE_API_KEY=your_google_api_key
5. Install Tesseract OCR:
   Windows: Download and install Tesseract OCR from https://github.com/UB-Mannheim/tesseract/wiki.
   Linux: Install Tesseract OCR using the following command:
      ```shh
   sudo apt-get install tesseract-ocr



### Usage

1. Run the application:
2. Open your web browser and navigate to http://127.0.0.1:5000.
3. Use the following routes to access different functionalities:

   /image: Upload images and extract text.
   /pdf: Upload PDF documents and extract text.
   /video: Summarize YouTube videos and local videos.
   
### Project Structure
  MA_13_DocSummariser/
├── app.py
├── imgtotext.py
├── pdftotext.py
├── video.py
├── templates/
│   ├── index.html
│   ├── imagetotext.html
│   ├── pdftotext.html
│   ├── video.html
├── static/
│   ├── css/
│   ├── js/
├── requirements.txt
└── .env

### Dependencies
Flask
Pillow
pytesseract
PyPDF2
langchain
langchain_google_genai
langchain_community
moviepy
speechrecognition
transformers
youtube_transcript_api
google-generativeai





   
   
