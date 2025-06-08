Document Retrieval System using NLP - A tool to search within ZIP folders and retrieve files containing specific keywords

DESCRIPTION:
  This project is an Intelligent Document Retrieval System that allows users to upload a ZIP file containing multiple documents (PDF, DOCX, TXT, PPTX). It intelligently extracts and searches for user-provided keywords using Natural Language Processing (NLP), and displays matching documents with a download option.

TECH USED:
  Python – core programming language,
  Natural Language Processing (NLP) – for keyword-based semantic search,
  NLTK – for tokenization and keyword matching,
  Streamlit – for building the interactive web interface,
  python-docx, PyPDF2, python-pptx – to extract content from different file formats & 
  zipfile – to extract ZIP archives.

HOW IT WORKS:
  i) User uploads a ZIP file containing various document formats.
  ii) The app extracts and reads contents from all supported documents.
  iii) It tokenizes and matches text using NLTK NLP tools.
  iv) It displays a list of matching file names with a download button for each.
  v) Supports: .pdf, .docx, .txt, .pptx.

HOW TO RUN IT:
Step 1: Clone the Repo

git clone https://github.com/Jason190703/Document-Retrieval-System-using-NLP.git
cd Document-Retrieval-System-using-NLP

Step 2: Install Requirements - Make sure you’re in a virtual environment (optional but recommended):

pip install -r requirements.txt

Step 3: Run the App

streamlit run app.py

Then open the local URL shown in your terminal (usually http://localhost:8501) in your browser.

SAMPLE OUTPUT:
![image](https://github.com/user-attachments/assets/c96d2df3-9b79-4ac0-8cdc-98f2b14db466)

