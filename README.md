# Retrieval-Augmented Generation (RAG) Pipeline
This repository contains the implementation of a Retrieval-Augmented Generation (RAG) pipeline. The goal is to enhance the performance of a standard Question Answering (QA) model by leveraging relevant documents from a vector database (Pinecone VectorDB).

## Overview
The RAG pipeline involves the following steps:

1. Document Reading and Preprocessing: Load and preprocess the dataset.
2. Chunking Documents for Embedding Generation: Split documents into sentences for fine-grained embedding generation.
3. Embedding Generation and Insertion into Pinecone VectorDB: Generate embeddings using a sentence transformer model and insert them into Pinecone VectorDB.
4. Retrieval of Relevant Documents: Retrieve relevant document chunks based on query embeddings.
5. Generating Answers Using Retrieved Documents: Use the retrieved documents to augment the query and generate accurate answers using a generative model.
   
## Setup Instructions
1. Clone the Repository
   ```bash

   ```
