# PDF Chat Application with Gemini AI

This is a Streamlit application that allows users to interactively ask questions based on the content of PDF documents using Google's Generative AI model, Gemini. The application extracts text from uploaded PDF files, processes the text to create a searchable index, and then enables users to input questions. The Gemini AI model then provides answers based on the context provided in the PDF documents.

## Features

- Extracts text from PDF files using PyPDF2 library.
- Splits the extracted text into smaller chunks for efficient processing.
- Creates a vector store from the text chunks using LangChain's FAISS library and Google's Generative AI Embeddings.
- Utilizes LangChain's conversational chain to provide answers based on the context of the PDF documents.
- Provides a user-friendly interface with Streamlit for uploading PDF files and asking questions.

   
