

# **StudyMate: AI Document Helper**



Above: A high-level overview of the workflow for StudyMate.

🌟 Overview

StudyMate is a Streamlit-based application that enables users to query their research papers or study material using advanced AI models. The tool supports:

PDF uploads for dynamic input
Document chunking and vector database creation
Question-answering based on the document context
Integration with cutting-edge models like Groq, Llama3, and HuggingFace Embeddings
This project is perfect for students, researchers, or anyone looking to get quick insights from their documents.

---

🛠 Features

PDF Ingestion: Upload one or multiple PDFs for querying.
Vector Database Creation: Automatically processes uploaded files into searchable embeddings.
Interactive Q&A: Ask questions and get context-aware answers.
Streamlit UI: User-friendly interface for seamless interaction.

---

🚀 Workflow

Upload PDFs: Uploaded IPSEC study material(a chapter from Cryptography and Network Security).
Document Processing: PDFs are split into smaller chunks and converted into embeddings using HuggingFace models.
Vector Database: The chunks are stored in a FAISS vector database for efficient retrieval.
Question Answering: Using Groq or Llama3, queries are answered based on the most relevant document chunks.
<img width="963" alt="Screenshot 2025-01-13 at 9 08 30 PM" src="https://github.com/user-attachments/assets/cde9a201-820f-4d6d-bc22-7cbd7e4a0014" />

---
📂 Project Structure 

<img width="704" alt="Screenshot 2025-01-13 at 9 28 42 PM" src="https://github.com/user-attachments/assets/fd9be794-fca6-4fbc-93de-9a77e282ce0a" />

---


