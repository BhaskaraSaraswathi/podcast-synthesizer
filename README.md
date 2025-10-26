# podcast-synthesizer
## 🎙️ PDF-to-Podcast Generator

## Overview
This project is a **Podcast Generator** that converts a PDF document into a **multi-episode podcast series**. It extracts text and images from a PDF, processes the content using AI (Google Gemini API), and generates podcast scripts, audio files, and discussion questions.

---

## Features
- Extracts text from PDFs using **pdfplumber**
- Extracts images from PDFs using **PyMuPDF (fitz)**
- Tokenizes and chunks document text for episode creation
- Generates structured podcast scripts using **Google Gemini AI**
- Converts scripts to audio using **Google Text-to-Speech (gTTS)**
- Provides discussion questions based on document content
- Web-based interactive UI using **Streamlit**

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo.git
```

2.Navigate to the project folder:
```bash
cd your-repo
```
3.Install dependencies using the requirements.txt file:
```bash
pip install -r requirements.txt
```
Setup & Usage

## Run the Streamlit App

1.Open Command Prompt (Windows), Terminal (Mac/Linux), or Git Bash.

2.Navigate to the project folder where your script is located.

3.Run the app:
``` bash
streamlit run script.py
```
4.Your default browser will open the app interface.

## Using the App

1.Upload a PDF file.

2.Enter your Google Gemini API Key.

3.Configure options:

  - Chunks per Episode: Adjust how much text goes into each podcast episode.

  - Max Chunk Size: Controls token size for document chunking.

4.Click Generate Podcast Series to create:

  - Podcast scripts (.txt files)

  - Audio files (.mp3)

  - Discussion questions

5.Download scripts and audio directly from the app.
