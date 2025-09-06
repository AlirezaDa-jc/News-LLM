# News-LLM

**News-LLM** is a Retrieval-Augmented Generation (RAG) system designed to process and generate insights from news articles. It combines Weaviate for vector-based search, Ollama for generative AI, a Flask backend API, and a Next.js frontend.

---

## 🚀 Project Structure

- **util**  
  Implementation of the RAG system:
  - Integrates [Weaviate](https://weaviate.io/) vector database.
  - Uses [Ollama](https://ollama.com/) for generative AI responses.
  - Dataset: [News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset)
  - Custom commands located in `ollama-models/`.

- **backend**  
  Flask API that:
  - Exposes endpoints to query Weaviate.
  - Returns generative AI responses for news articles.

- **front**  
  Next.js frontend using Tailwind CSS:
  - Interfaces with the Flask API.
  - Displays AI-generated responses based on keyword queries.

---

## ⚘️ Features

- Semantic search on news articles.
- Retrieval-augmented generation (RAG) with AI.
- Full-stack implementation with frontend and backend.
- Dockerized for easy deployment.

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** Next.js, Tailwind CSS  
- **AI & Database:** Ollama, Weaviate  
- **DevOps:** Docker, Docker Compose

---

## 📦 Getting Started

1. Clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/AlirezaDa-jc/News-LLM.git
```

2. Navigate to the project directory and start Docker Compose:

```bash
docker-compose up
```

3. Access the frontend at `http://localhost:3000`.

---

## 🎯 Key Learnings

- Implemented a full RAG pipeline from scratch.
- Gained experience with vector databases and AI integration.
- Developed a full-stack system combining Python backend and React frontend.
- Learned deployment strategies using Docker and Docker Compose.

---

## 📸 Screenshots / Demo

*(Add GIFs or images showing frontend UI and AI responses here.)*

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
