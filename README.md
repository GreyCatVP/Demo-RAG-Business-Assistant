# RAG Business Assistant (FastAPI + FAISS)

Лёгкий демо-сервис для контекстных ответов на базе RAG:
- загрузка текстов в векторный индекс (FAISS),
- поиск релевантных фрагментов,
- простые REST-эндпоинты для интеграции.

## Стек
- Python 3.10+
- FastAPI, Uvicorn
- LangChain, SentenceTransformers
- FAISS (CPU)
- Docker (опционально)

## Быстрый старт

### 1) Клонирование и окружение
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env

🧾 Licensed under the [MIT License](./LICENSE) — © 2025 Vladislav Popov  
Made with ❤️ using FastAPI, FAISS and LangChain.
