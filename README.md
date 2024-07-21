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
2.Create and activate a virtual environment:
  ```sh
  python -m venv venv
  source venv/bin/activate

3.Install the required packages:
  ```sh
  pip install -r requirements.txt


