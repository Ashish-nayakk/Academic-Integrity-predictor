# Academic-Integrity-predictor
An advanced academic integrity detection system that evaluates documents using NLP pipelines, vector embeddings, and stylometric profiling. It identifies plagiarism, AI-written content, paraphrasing patterns, and writing anomalies to create reliable integrity reports for academic and research use.
The project includes a modern Flask web application, a clean UI dashboard, and optional Ngrok integration for public access.

🚀 Features
🔹 1. Multi-Mode Plagiarism Checking

Text-to-Text Comparison
Paste two texts and get similarity highlights instantly.

One-to-One File Comparison
Upload two files (PDF, DOCX, TXT) and compare meaning-level similarity.

One-to-Many File Comparison
Compare a source file with multiple documents at once and view similarity results in a structured grid.

🔍 Core Capabilities

Semantic similarity detection using
SentenceTransformer (all-mpnet-base-v2)

Cosine similarity scoring

Highlighted plagiarized text with color-coded risk levels

Detailed sentence-level matching

Extract text from:

PDFs (via pdfplumber)

DOCX files (via python-docx)

TXT files

🎨 Frontend Highlights

Modern, gold-on-black premium UI

Animated similarity circle

Expandable highlight sections

Responsive design

Clean comparison results page

Smooth hover & fade animations

🛠️ Tech Stack
Backend

Python

Flask

Sentence Transformers

Torch

NLTK

pdfplumber

python-docx

Frontend

HTML5

CSS3

JavaScript

Deployment

Ngrok (optional public URL generation)

📊 Output Includes

Overall similarity percentage

Highlighted plagiarized segments

Side-by-side content comparison

Multi-document similarity grid

Sentence-level heatmap-style matching

🧩 Ideal For

Students

Teachers & Professors

Institutes ensuring academic honesty

Researchers verifying originality

Developers integrating plagiarism detection in workflow

📁 Repository Structure (recommended)
/static
    /css
    /js
/templates
    index.html
    compare.html
app.py
requirements.txt
README.md

📣 How It Works

User inputs or uploads text/files

System extracts and splits sentences

Embeddings are generated using Transformer models

Cosine similarity is calculated

Results + highlights are returned to UI
