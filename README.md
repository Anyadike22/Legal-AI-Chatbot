# Legal-AI-Chatbot

## Scripts for a Legal Chatbot

## GPU Availability Check

Ensures that a CUDA-compatible GPU is available for faster chatbot processing using PyTorch.

## Legal Text Preprocessing

Cleans legal text by removing special characters, lowercasing, and lemmatizing important words.
Helps improve the chatbot’s understanding of legal queries.

## Legal Named Entity Recognition (NER)

Extracts important legal entities (e.g., company names, dates, laws) from text using spaCy.
Useful for chatbot responses that require structured legal information.

## Embedding Legal Texts

Converts legal documents into vector embeddings using a transformer model.
Helps the chatbot retrieve relevant legal clauses based on a user’s query.

## FAISS-Based Legal Document Search

Stores legal document embeddings in a FAISS index for fast similarity search.
Enables the chatbot to retrieve relevant legal clauses instead of just generating answers.

## Legal Chatbot Response Generation

Uses a pre-trained transformer model to generate AI-powered legal responses to user queries.
Can be improved with domain-specific models for better accuracy.
Overall Purpose
These scripts work together to build an AI-powered legal chatbot that can:
✅ Understand legal language using NLP preprocessing and NER.
✅ Retrieve relevant legal information with FAISS-based search.
✅ Generate accurate legal answers using a transformer-based model.
