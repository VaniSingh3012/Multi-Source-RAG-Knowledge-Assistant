# 🚀 Multi-Source RAG Knowledge Assistant

An AI-powered Retrieval-Augmented Generation (RAG) system that enables users to interact with PDFs, documents, and knowledge bases using both text and voice queries.

Built using **Groq LLM**, **FAISS Vector Search**, **Whisper Speech Recognition**, and **Streamlit**.

---

## 👩‍💻 Team

| Name | Role | GitHub |
|------|------|--------|
| Vani Singh | Developer | [@VaniSingh3012](https://github.com/VaniSingh3012) |
| Sonal Shrivastava | Developer | [@shrivastavasonal62-oss](https://github.com/shrivastavasonal62-oss) |

🎓 B.Tech Computer Science Engineering — ABES Engineering College, Ghaziabad (Batch 2027)

---

## ✨ Features

### 📄 Document Intelligence
- Upload and process PDF documents
- Semantic search across uploaded knowledge sources
- Context-aware question answering

### 🎤 Voice Assistant
- Voice-based question input using OpenAI Whisper
- Hands-free interaction with documents

### 🤖 AI-Powered Responses
- Powered by Groq LLM (Llama 3.1)
- Fast and accurate context-aware responses

### 📝 Smart Learning Tools
- Automatic MCQ quiz generation
- Summary generation from complex documents
- Exam notes creation
- Key concept extraction

### 📥 Export Features
- Download AI-generated answers as PDF
- Export study material

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Streamlit, HTML/CSS |
| LLM | Groq API (Llama 3.1) |
| Speech-to-Text | OpenAI Whisper |
| Vector Database | FAISS |
| Embeddings | Sentence Transformers |
| Data Processing | PyPDF, NumPy, Pandas |
| Deployment | Streamlit Community Cloud |

---

## 🏗️ System Architecture

```
User Query (Text / Voice)
          │
          ▼
PDF / Knowledge Base
          │
          ▼
Embedding Generation (Sentence Transformers)
          │
          ▼
FAISS Vector Search
          │
          ▼
Relevant Context Retrieval
          │
          ▼
Groq LLM (Llama 3.1)
          │
          ▼
Generated Answer
```

---

## 📂 Project Structure

```
Multi-Source-RAG-Knowledge-Assistant/
│
├── streamlit_app.py       # Main Streamlit app
├── ask_question.py        # Question answering logic
├── search_transcripts.py  # Transcript search
├── preprocess_json.py     # JSON preprocessing
├── process_incoming.py    # Incoming data processing
├── mp3_to_json.py         # Audio to JSON converter
├── video_to_mp3.py        # Video to audio converter
├── requirements.txt       # Python dependencies
├── styles.css             # Custom styling
├── vectors.joblib         # Saved FAISS vectors
├── jsons/                 # JSON data folder
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/VaniSingh3012/Multi-Source-RAG-Knowledge-Assistant.git
cd Multi-Source-RAG-Knowledge-Assistant
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure Environment
Create a `.env` file:
```
GROQ_API_KEY=your_groq_api_key_here
```

### 4. Run Application
```bash
streamlit run streamlit_app.py
```
App will open at `http://localhost:8501`

---

## 🎯 Use Cases
- AI Study Assistant for students
- Research paper analysis
- Document-based Q&A chatbot
- Exam preparation tool
- Voice-powered knowledge retrieval

---

## 📈 Future Enhancements
- Multi-PDF cross-document reasoning
- Chat history with database
- User authentication system
- Citation-based answers
- OCR integration for scanned PDFs
- Agentic workflows

---

## ⭐ If you like this project
Give this repository a star ⭐ and share it!
