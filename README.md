# Mr.HelpMate-AI

# Insurance Policy Document Retrieval and Generation System

# Overview

This repository hosts a powerful Retrieval Augmented Generation (RAG) system designed specifically for insurance policy documents. The system integrates advanced techniques in text embedding, search, and generation, ensuring accurate retrieval and generation of information from lengthy policy documents.

# RAG Architecture

![Project Architecture]("D:\Git_Raju\Mr.HelpMate-AI\data\image\Picture1.png")

# Features

PDFPlumber Integration: Utilizes PDFPlumber library for extracting text from insurance policy PDF documents, ensuring seamless data extraction.

Text Embedding: Employs OpenAI's "text-embedding-ada-002" model for effective chunking and embedding of extracted text, optimizing retrieval accuracy.

Search Layer: Implements a search layer that enables querying against the embedded text chunks, with a cache mechanism for improved performance.

Generation Layer: Leverages GPT-3.5-turbo model for generating coherent and contextually relevant answers based on the retrieved information.

# Getting Started

Clone the repository:
git clone https://github.com/rajuaiml777/Mr.HelpMate-AI.git

cd Mr.HelpMate

# Install dependencies:

pip install -r requirements.txt

Follow the setup instructions in the documentation to configure and run the system.

# Usage

Extract insurance policy text using PDFPlumber.

Preprocess and embed the text chunks using the chosen embedding model.

Design queries for the search layer and retrieve relevant chunks.

Generate answers using the retrieved information and the generation model.

Experiment with different strategies and models to optimize performance.

# Contribution Guidelines

Contributions to enhance the system's functionality, performance, or documentation are welcome! Please refer to the CONTRIBUTING.md file for guidelines.

# Acknowledgements

OpenAI for providing access to advanced text embedding and generation models.
PDFPlumber developers for creating a reliable tool for PDF text extraction.
Hugging Face for hosting pre-trained models and facilitating experimentation.
