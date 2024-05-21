# Chatbot System

## Overview

This chatbot system combines advanced AI technologies to deliver intelligent, contextually relevant responses to user queries.

## Setup

1. **API Configuration**: Set up access to Google’s Generative AI services with an API key.
2. **Model Initialization**: Initialize the 'gemini-pro' pre-trained model.
3. **PDF Processing**: Use PyMuPDF and NLTK to parse PDFs and extract text.
4. **Sentence Encoding**: Encode sentences using the 'all-mpnet-base-v2' model.
5. **Similarity Matching**: Apply cosine similarity to find semantically similar sentences.

## Usage

The system enriches user queries with additional context from PDFs, alternating responses with and without this context to ensure comprehensive and relevant interactions.

