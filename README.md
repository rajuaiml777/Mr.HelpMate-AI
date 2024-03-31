# Mr.HelpMate-AI

## Insurance Policy Document Retrieval and Generation System

Welcome to Mr.HelpMate-AI, a powerful Retrieval Augmented Generation (RAG) system tailored for insurance policy documents. Our system integrates cutting-edge techniques in text embedding, search, and generation, ensuring accurate retrieval and generation of information from lengthy policy documents.

### RAG Architecture

![Project Architecture](https://github.com/rajuaiml777/Mr.HelpMate-AI/blob/main/data/image/Picture1.png)

### Features

- **PDFPlumber Integration**: Seamlessly extract text from insurance policy PDF documents using PDFPlumber library.
  
- **Text Embedding**: Employ OpenAI's "text-embedding-ada-002" model for effective chunking and embedding of extracted text, optimizing retrieval accuracy.
  
- **Search Layer**: Implement a search layer enabling querying against the embedded text chunks, with a cache mechanism for improved performance.
  
- **Generation Layer**: Leverage GPT-3.5-turbo model for generating coherent and contextually relevant answers based on the retrieved information.

### Getting Started

1. **Clone the repository:**
```bash
  git clone https://github.com/rajuaiml777/Mr.HelpMate-AI.git

  cd Mr.HelpMate
```

2. **Install dependencies:**
```bash  
  pip install -r requirements.txt
```

3. **Follow the setup instructions in the documentation to configure and run the system.**

### Usage

1. Extract insurance policy text using PDFPlumber.
2. Preprocess and embed the text chunks using the chosen embedding model.
3. Design queries for the search layer and retrieve relevant chunks.
4. Generate answers using the retrieved information and the generation model.
5. Experiment with different strategies and models to optimize performance.

## Contribution
Contributions of any kind are welcome.

### Acknowledgements

- OpenAI for providing access to advanced text embedding and generation models.
- PDFPlumber developers for creating a reliable tool for PDF text extraction.
- Hugging Face for hosting pre-trained models and facilitating experimentation.

For more details, visit our [GitHub repository](https://github.com/rajuaiml777/Mr.HelpMate-AI). Let's make insurance policy handling smarter and easier! 🚀
