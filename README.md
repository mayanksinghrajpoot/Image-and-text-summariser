# 📄 Image and Text Summariser

A lightweight Python-based tool that converts long text content into short, meaningful summaries.

> **Useful for:** Students, developers, and researchers who need quick, concise summaries from large text files.

## 🚀 Features

* ✔️ **Efficient:** Summarizes long text into short, readable content.
* ✔️ **Batch Processing:** Supports multiple text input files.
* ✔️ **Clean Code:** Simple and easy-to-understand Python structure.
* ✔️ **Lightweight:** No heavy machine learning dependencies.
* ✔️ **Educational:** A beginner-friendly project for NLP fundamentals.

## 📂 Project Structure

```text
📁 Image-and-text-summariser
│
├── prompt_app.py                  # Main executable summarizer script
├── prompt_lib.py                  # Helper functions for text processing
│
├── basics.txt                     # Sample input file
├── qa.txt                         # Sample input file
├── analysis_positive.txt          # Sample analysis file
├── analysis_negative.txt          # Sample analysis file
├── summarization_content.txt      # Additional sample input
│
└── README.md                      # Project documentation



🛠️ Requirements

Python 3.x

No external dependencies (unless you add NLP libraries later)

If you later use any library, add them in a requirements.txt.

📥 Installation
git clone https://github.com/mayanksinghrajpoot/Image-and-text-summariser
cd Image-and-text-summariser


(Optional) Create a virtual environment:

python -m venv venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows

▶️ Usage
Run the summariser
python prompt_app.py

How it works

You place your text files (e.g., basics.txt, qa.txt, etc.)

The script reads the file

It generates a shorter summarized version

Output is printed on the console

If you plan to support command-line arguments later, you can add:

python prompt_app.py input.txt

📝 Example
Input (basics.txt):
Artificial Intelligence refers to the simulation of human intelligence in machines...

Output Summary:
AI is the simulation of human intelligence in machines designed to perform tasks intelligently.

🌱 Future Enhancements (Optional)

Add PDF → text → summary support

Add image-to-text (OCR) → summary

Add fixed summary length (short / medium / detailed)

Add a simple GUI or web interface

Add an API endpoint

Use NLP libraries like spaCy / NLTK / transformers

🤝 Contributing

Contributions are always welcome!

Steps:

Fork this repository

Create your feature branch

Commit changes

Open a pull request
