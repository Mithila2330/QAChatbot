BUSINESS DOMAAIN QA CHATBOT : 

This project implements a Retrieval-Augmented Generation (RAG)-based Question Answering Chatbot designed to answer domain-specific business queries. It retrieves accurate responses from a custom knowledge base using semantic search combined with vector similarity techniques.

FEATURES

Retrieval-based question answering system

Utilizes Sentence Transformers for semantic embeddings

FAISS vector search for fast and efficient retrieval

Synonym mapping to handle varied user phrasing

Similarity thresholding to ensure response accuracy

Fully customizable for different business or institutional datasets

TECHNOLOGIES USED

(1)Python

(2)FAISS

(3)Sentence Transformers

(4)Google Colab

WORKING
  
  [1]  Prepares a knowledge base with business-related information.
  
  [2]  Converts textual data into semantic embeddings using pre-trained models like all-MiniLM-L6-v2.
  
  [3]  Builds a FAISS index to allow quick similarity searches.
  
  [4]  Uses synonym mapping to interpret different user query styles.
  
  [5]  Returns the most relevant sentence from the knowledge base or responds appropriately if no close match is found.

USECASES

This chatbot can be used by businesses or educational institutions to automate FAQ responses, improve information accessibility, and provide a lightweight, offline-friendly answering system without relying on external APIs.

HOW TO RUN

1) Open the Colab Notebook provided.

2) Install required dependencies and set up the knowledge base.

3) Run the cells in sequence.

4) Enter your query in the provided input box to receive an instant response.

