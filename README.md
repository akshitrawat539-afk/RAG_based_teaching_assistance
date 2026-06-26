# 🎓 EduNexus Knowledge Explorer

> **An AI-powered Retrieval-Augmented Generation (RAG) application that transforms educational videos into an interactive knowledge base.**

EduNexus Knowledge Explorer enables users to upload educational videos, automatically transcribe them, generate semantic embeddings, and ask questions in natural language. By combining **Whisper**, **LangChain**, **ChromaDB**, and locally hosted **Llama 3/Mistral** models through **Ollama**, the application delivers accurate, context-aware responses—all through a user-friendly **Streamlit** interface.

---

## 🌐 Live Demo

🔗 **Try the application:**  
https://ragbasedteachingassistant-6q6gmyzur3bbh9a6gi7dae.streamlit.app/

---

## ✨ Key Features

- 📹 Upload educational video lectures
- 🎙️ Extract audio using FFmpeg
- 📝 Transcribe speech with Whisper
- ✂️ Automatically split transcripts into chunks
- 🧠 Generate semantic embeddings for efficient retrieval
- 🔍 Perform context-aware semantic search
- 🤖 Answer questions using Llama 3 or Mistral via Ollama
- 💻 Interactive and responsive Streamlit interface
- 🔒 Fully offline AI processing

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Streamlit | User Interface |
| FFmpeg | Audio Extraction |
| Whisper | Speech-to-Text |
| LangChain | RAG Pipeline |
| ChromaDB | Vector Database |
| Sentence Transformers | Embedding Generation |
| Ollama | Local LLM Runtime |
| Llama 3 / Mistral | Question Answering |

---

## 📁 Project Structure

```text
EduNexus-Knowledge-Explorer/
│
├── app.py
├── requirements.txt
├── README.md
│
├── videos/
├── audio/
├── transcripts/
├── embeddings/
├── screenshots/
└── utils/
```

---

## ⚙️ Workflow

```text
Upload Video
      │
      ▼
Extract Audio (FFmpeg)
      │
      ▼
Speech-to-Text (Whisper)
      │
      ▼
Text Chunking
      │
      ▼
Generate Embeddings
      │
      ▼
Store in ChromaDB
      │
      ▼
Semantic Retrieval
      │
      ▼
Llama 3 / Mistral (Ollama)
      │
      ▼
Generate Answer
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/vristi20/EduNexus-Knowledge-Explorer.git
cd EduNexus-Knowledge-Explorer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Install Ollama

Download Ollama and pull your preferred model:

```bash
ollama pull llama3
```

or

```bash
ollama pull mistral
```

### Launch the Application

```bash
streamlit run app.py
```

---



```markdown
### Home Page
![Home](screenshots/home.png)

### Upload Interface
![Upload](screenshots/upload.png)

### Chat Interface
![Chat](screenshots/chat.png)
```

---

## 🎯 Applications

- AI Learning Assistant
- Lecture Question Answering
- Educational Video Search
- Offline Knowledge Retrieval
- Student Revision Tool
- Self-Paced Learning

---

## 🔮 Future Scope

- Multiple video support
- PDF and document integration
- Chat history
- Source citations
- User authentication
- Cloud deployment
- Multi-language transcription
- Voice-based interaction

---

## 👨‍💻 Author

**Akshit Rawat**



---

