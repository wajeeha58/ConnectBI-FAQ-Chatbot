# ConnectBI-FAQ-Chatbot
A chatbot using Streamlit and LangChain to answer FAQs from PDF documents related to Connect-BI, integrating Google Generative AI for accurate responses.
ConnectBI-FAQ-Chatbot

# Chat with PDF using Gemini 💬

This Streamlit application allows users to ask questions based on the content of uploaded PDF files. It leverages Google's Generative AI (Gemini) for answering questions and utilizes vector-based similarity search for efficient document retrieval.

## Features

- **PDF Upload**: Upload multiple PDF files.
- **Question Input**: Enter questions related to the uploaded PDF content.
- **AI-Powered Answers**: Utilizes Google's Generative AI to answer questions based on the provided PDF context.
- **Vector-Based Search**: Uses FAISS for vector-based similarity search on PDF text chunks.

## Requirements

- Python 3.x
- Streamlit
- PyPDF2
- langchain
- langchain_google_genai
- FAISS
- dotenv

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
