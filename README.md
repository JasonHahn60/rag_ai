Overview
This project implements a Retrieval-Augmented Generation (RAG) system using Google Cloud Vertex AI Agent Builder to perform semantic search and question-answering on book texts. The system leverages Google's Gemini-1.5-Flash-001 model for retrieval and answer generation.

How It Works
1. Data Ingestion
Book texts are uploaded to a Google Cloud Storage bucket.
Agent Builder automatically parses, chunks, and vectorizes the texts.

2. Retrieval & Answer Generation
User queries are compared against vectorized book text embeddings using semantic search.
Relevant chunks are retrieved and passed to Gemini-1.5-Flash-001 for answer generation.

3. Deployment & Access
The RAG system is integrated into a web application using Google Agent Builder’s API.
Users can query the model via an embedded search widget.

How to Use
Visit [jasonhahn60.github.io](https://jasonhahn60.github.io/) and enter a query in the search bar under AI Showcase.
The model retrieves relevant book passages and generates an answer.
