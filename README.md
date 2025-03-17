```markdown
# HelpMateAI: Semantic Search and Question Answering for Insurance Documents

## Overview

HelpMateAI is a project that aims to address the challenge of locating specific information within complex insurance documents. It combines semantic search with powerful language models to deliver accurate and context-aware answers to user queries from within insurance documents. The core features of the project include:

- PDF processing and text extraction
- Semantic search to retrieve relevant insurance document sections
- AI-powered question answering to provide direct answers and citations

The project aims to streamline information retrieval, save time for policyholders and agents, and potentially enhance decision-making based on policy terms.

## Features

- **PDF Preprocessing**: Extracts text from insurance PDFs using the pdfplumber library.
- **Semantic Search**: Implements semantic search using ChromaDB and OpenAI embeddings to enhance the relevance of search results compared to keyword-based methods.
- **Question Answering**: Leverages OpenAI language models for natural language processing to pinpoint answers and provide citations within insurance documents.
- **Potential Additional Features**: Table extraction and reformatting, answer summarization.

## Technology Stack

- **Python**
- **pdfplumber**: PDF parsing
- **Ollama 3.2**: Text embeddings, language model access
- **ChromaDB**: Semantic search database with embedding storage
- **Sentence Transformers**: Cross-encoder for result re-ranking (optional)
- **Other Libraries**: Langchain Framework, pandas for JSON parsing and DataFrame manipulations

## Challenges and Lessons Learned

The project faced challenges such as handling complex PDF structures, adapting to insurance-specific terminology, finding the ideal balance in answer granularity, and optimizing API costs. Lessons learned include the importance of thorough PDF analysis, domain adaptation for language model accuracy, the potential benefits of hybrid retrieval techniques, and the need for cost-effective architectures.

## Future Work

Potential future work includes:

- Enhanced User Interface
- Multi-Document Question Answering
- Policy Comparison
```

Demo Sample -

![image](https://github.com/user-attachments/assets/012df83a-0d4a-44f2-8399-66b2e97c0681)

