# AI RAG - PDF Search in multiple documents using Gemma 2 2B on Colab

This project demonstrates a pipeline for extracting, processing, and querying text data from PDF documents on Google Colab using natural language processing (NLP) techniques and Google's open-source model Gemma 2 2B. The system allows users to input a query, which is then answered based on the content of the PDFs.

## Features
- PDF Text Extraction: Extracts text from PDFs using PyPDF2.
- Text Chunking: Splits extracted text into manageable chunks.
- Embedding Generation: Uses SentenceTransformer to convert text chunks into embeddings.
- FAISS Indexing: Builds a FAISS index for efficient similarity search.
- Query Matching: Finds the most similar text chunks to a user query.
- Response Generation: Uses a transformer model to generate responses based on the most relevant chunks.

## Parameters

The PDFs must be uploaded to a folder called "PDFs" inside your /content on Google Colab. If you run the code locally, make sure you change it to your desired path.
