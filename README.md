# Summary
This repo is a simple project testing some fundamentals of AI based scripts in Python.

The functionality is simple:
- 01_Vectorization: Reads a PDF file with knowledge about a company, vectorizes it, and stores in a chroma database
- 02_Scraper: Reads news, judges which are relevant to the company, processes the information and saves it in a structured database
- 03_EmailShooter: Reads the processed data and shoots e-mails
- 04_Site: A simple Streamlit app as a interface to a chatbot that answers questions based of the gathered news, the vectorized knowledge of the company and a search engine tool
