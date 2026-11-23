<div align="center">

# Omar Elsayed

### AI Engineering · Machine Learning · LLM Applications

I build document search and question-answering tools, machine learning pipelines, and multi-agent prototypes. My projects focus on clear interfaces, reproducible evaluation, and documented limitations.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-2563EB?style=flat-square)](https://omar-elsayed-portfolio.vercel.app/)

</div>

## Featured repositories

### [Omar’s Library](https://github.com/OmarElsayed09/omars-library)

A local-first document search and Q&A workspace for Arabic and English. It combines BM25 and semantic retrieval and links answers to cited PDF pages.

`Python` · `FastAPI` · `React` · `Ollama` · `ChromaDB`

### [MediRAG — Clinical Guidelines Assistant](https://github.com/OmarElsayed09/medirag-clinical-assistant)

A clinical-guideline question-answering prototype combining dense and keyword retrieval with cross-encoder reranking. Includes source-page citations, clinical decision-support utilities, FastAPI and Streamlit interfaces, Docker configuration, and automated tests. **Educational use only; not validated for clinical decisions.**

`Python` · `LangChain` · `ChromaDB` · `BM25` · `FastAPI` · `Docker`

### [Hotel Booking Cancellation & ADR Prediction](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction)

A machine-learning application for estimating hotel booking cancellation risk and average daily room rate. Includes a multi-source training pipeline, chronological evaluation, batch prediction, and interactive web interfaces. Results are based on historical data and require validation for new hotels and time periods.

`Python` · `Scikit-learn` · `Pandas` · `FastAPI` · `Streamlit`

### [Smart Emergency Incident Response](https://github.com/OmarElsayed09/smart-emergency-incident-response)

An experimental multi-agent workflow for structuring incident reports, retrieving procedure context, reviewing evidence and safety flags, and generating a proposed response plan with human-review status. Uses simulated resources; **not an operational emergency dispatch system**.

`Python` · `LangGraph` · `Groq` · `ChromaDB` · `Streamlit`

### [Smart Document Assistant — LLM RAG Chatbot](https://github.com/OmarElsayed09/LLM-RAG-Chatbot)

A document-question-answering prototype supporting PDF, TXT, DOCX, CSV, and PPTX ingestion, text chunking, FAISS indexing, Groq-powered answers, and a Gradio interface. Uses top-k semantic retrieval to select relevant passages; **a labeled answer-quality benchmark is not yet established.**

`Python` · `LangChain` · `FAISS` · `Hugging Face` · `Groq` · `Gradio`

## Engineering notes

The [Portfolio Quality & Verification Report](docs/PORTFOLIO-QUALITY.md) documents evaluation methods, workflow results, and known limitations.

[Omar’s Library checks](https://github.com/OmarElsayed09/omars-library/actions) · [Document RAG checks](https://github.com/OmarElsayed09/LLM-RAG-Chatbot/actions) · [Emergency workflow checks](https://github.com/OmarElsayed09/smart-emergency-incident-response/actions) · [MediRAG checks](https://github.com/OmarElsayed09/medirag-clinical-assistant/actions) · [Hotel ML checks](https://github.com/OmarElsayed09/Hotel-Booking-Cancellation-ADR-Prediction/actions)

## Technical stack

- **Languages and data:** Python, SQL, Pandas, NumPy
- **Machine learning:** Scikit-learn, PyTorch, TensorFlow
- **Retrieval and LLMs:** BM25, LangChain, LangGraph, ChromaDB, FAISS, Hugging Face, Groq, Ollama
- **Applications and tooling:** FastAPI, Flask, React, Streamlit, Gradio, Git, Docker, Jupyter
