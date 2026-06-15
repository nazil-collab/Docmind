# 🧠 DocMind — AI Document Intelligence Platform

Ask questions about any PDF in plain English. Get answers with citations.

## Stack
- **Backend:** Python, FastAPI, PostgreSQL + pgvector
- **AI:** OpenAI (embeddings + GPT-4o-mini)
- **Frontend:** Streamlit
- **Infrastructure:** Docker, Docker Compose
- **Deployed on:** Render + Streamlit Cloud

## Quick Start

1. Clone the repo: `git clone https://github.com/yourusername/docmind`
2. Copy env file: `cp .env.example .env` and fill in your OpenAI key
3. Start everything: `docker-compose up --build`
4. Open the app: http://localhost:8501

## Project Structure
- `backend/` — FastAPI server, RAG pipeline, database logic
- `frontend/` — Streamlit UI
- `docker-compose.yml` — runs everything together