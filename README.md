# RAG-Based Chatbot using Large Language Models

This project implements a **Retrieval-Augmented Generation (RAG)** based chatbot
that enhances Large Language Models (LLMs) with external knowledge retrieval to
generate accurate, reliable, and context-aware responses.

The system is designed to reduce hallucinations by grounding responses in
retrieved documents instead of relying solely on the LLM’s internal knowledge.

---

## Problem Statement
Traditional LLM-based chatbots generate responses purely from pre-trained data,
which can result in hallucinations, outdated information, and weak performance
on domain-specific queries.

This project addresses these limitations by implementing a **RAG architecture**
that retrieves relevant information before generating responses.

---

## Solution Overview
The chatbot follows a **Retrieval-Augmented Generation (RAG) pipeline**:

1. User query is converted into vector embeddings
2. Relevant documents are retrieved using similarity search
3. Retrieved context is passed to the LLM
4. The LLM generates a grounded, context-aware response

This approach significantly improves response accuracy and reliability.

---

## Key Features
- Retrieval-Augmented Generation (RAG) architecture
- Context-aware and grounded responses
- Reduced hallucinations compared to vanilla LLMs
- Interactive chatbot interface
- End-to-end deployed application
- Modular and scalable design

---

## Tech Stack
- Python
- Large Language Models (LLMs)
- Vector Embeddings
- Similarity Search / Retrieval
- Retrieval-Augmented Generation (RAG)
- Streamlit
- GitHub & Streamlit Cloud (Deployment)

---

## Application Workflow
1. Document ingestion and preprocessing
2. Embedding generation for documents
3. Vector-based similarity search
4. Context injection into LLM prompts
5. Response generation
6. User interaction via Streamlit UI

---

## Live Demo
🔗 **Streamlit Application:**  
https://ragbasedchatbot-lucpm7xqn6cdtzkfe4wayd.streamlit.app/

---

