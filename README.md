# YouTubeChat-using-LangChain 🎥🤖

This project is a **multimodal Retrieval-Augmented Generation (RAG) system** that enables users to **chat with a YouTube lecture video** using natural language queries.

The system converts video content into structured knowledge by processing audio, generating embeddings, and performing **semantic search** to provide accurate, context-aware answers.

---

## 🚀 Project Overview

Given a YouTube video URL, the application:
1. Downloads the audio from the video  
2. Converts speech to text using **Whisper Large v3**  
3. Splits the transcript into meaningful chunks  
4. Generates semantic embeddings for each chunk  
5. Stores embeddings in a **Chroma vector database**  
6. Retrieves only the most relevant chunks for a user query  
7. Uses a **Groq-powered LLM** to generate the final response  

This allows users to ask questions like:
- *What is Python?*
- *Are loops covered in this lecture?*
- *Is data structures discussed in the video?*

---

## 🧠 Key Features

- 🎥 Multimodal RAG (Video → Audio → Text → Knowledge)
- 🗣️ Speech-to-text using **Whisper Large v3**
- ✂️ Efficient chunking with **RecursiveCharacterTextSplitter**
- 🧬 Semantic embeddings using **Google Gemini Embedding model**
- 📦 Vector storage & retrieval with **ChromaDB**
- 🔍 Semantic search (retrieves only relevant chunks)
- 🤖 Context-aware answers using **Groq LLM**
- 🧱 Built entirely using **LangChain (Python)**

---

## 🏗️ Architecture Flow




---

## 🛠️ Tech Stack

- Python
- LangChain
- Whisper Large v3
- Groq OpenAI Chat Model
- Google Gemini Embeddings
- ChromaDB

---

## 🎯 Learning Outcomes

- Understanding real-world **RAG architecture**
- Working with **multimodal data (audio + text)**
- Chunking strategies for long documents
- Semantic search vs keyword search
- Using retrievers, prompt templates, and output parsers
- Building GenAI pipelines with **LangChain**

This project was completed as part of an intensive **7-day GenAI learning sprint**, covering **LangChain, RAG, and AI agents with tools**.

---

## 🔮 Future Enhancements

- Source citation with timestamps
- Conversational memory
- LangGraph-based agent orchestration
- Hybrid search (BM25 + semantic)
- Web-based user interface

---

## 📌 Use Case

This system is especially useful for:
- Long educational lectures
- Technical tutorials
- Interview preparation videos
- Content summarization and exploration

---

⭐ If you find this project useful, feel free to star the repository!
