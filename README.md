# RAG Chatbot (Databricks)
Dette prosjektet er et RAG-basert chatbot bygget i Databricks. 
Målet er å kunne hente informasjon fra PDF/MD-dokumenter, generere embeddings og svare på spørsmål med kildehenvisning.

## Struktur
- `notebooks/` - Databricks notebooks (ingest, retrieval, eval)
- `src/rag/` - Python-moduler (chunking, embed, retriever, prompts)
- `test/` -Pytest-enhetstester
- `requirements.txt` - Python-avhengigheter
- `.gitignore` - 
