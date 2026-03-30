# Mini-RAG-Chatbot

# **LLM/RAG Demonstration**
### Problem Statement
* Traditional chatbots
* Hallucinate answers
* Cannot access documents
* Do not use company-specific knowledge

### Goal
Build a **RAG pipeline** that:
* Accepts documents
* Creates embeddings
* Stores them in a vector database
* Retrieves relevant chunks
* Generates context-aware answers using LLM

### AI System Integration
* AI system integration means connecting AI models with real-world applications, and user interfaces to build a complete working system.
* Example: RAG Chatbot

### Workflow System
* Design an AI system that:
  * Accepts user queries
  * Retrieves relevant knowledge
  * Generates contextual anwers
  * Minimizes hallucination

* User -> Query Processing -> Embedding -> Vector Search -> Context Retrieval -> LLM -> Response -> UI

### Build mini RAG chatbot pipeline
||
|:--:|
|User Question|
|Convert to Embedding|
|Compare with document Embeddings|
|Calculate Cosine Similarity|
|Find Most Similar Document|
|Retrun Answer|

### Deployment
* Streamlit is an open-source Python framework used to build interactive web applications for GenAI, data science and machine learning and AI quickly without needing frontend development.

### Streamlit Installation
pip install streamlit sentence-transformers scikit-learn

streamlit run chatbot_project.py
