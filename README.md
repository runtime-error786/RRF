# PDF Document QA System with Reciprocal Rank Fusion

This project is a question-answering (QA) system built using LangChain that processes PDF documents, splits them into manageable chunks, stores them in a vector store (Chroma), and retrieves the most relevant information to answer user queries. The system enhances retrieval accuracy using a Reciprocal Rank Fusion (RRF) technique, leveraging related queries and a ranking mechanism to improve the relevance of the results.

## Features

- **PDF Document Loading**: Automatically loads and processes PDF files from a specified folder.
- **Text Chunking**: Splits the document text into chunks of a manageable size for efficient retrieval.
- **Vector Store**: Stores document chunks in a vector store using embeddings generated by a sentence-transformer model.
- **Reciprocal Rank Fusion (RRF)**: Improves retrieval accuracy by generating related queries, retrieving results for each, and combining them using RRF.
- **Question-Answering**: Retrieves relevant chunks of text to answer user queries with high accuracy.
