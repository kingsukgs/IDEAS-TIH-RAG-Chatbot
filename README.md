# IDEAS-TIH RAG Chatbot  
### *Open-Source Retrieval-Augmented AI Assistant for IDEAS-TIH (ISI Kolkata)*

---

## 📌 Overview  
This project implements a **Retrieval-Augmented Generation (RAG)** based AI Assistant designed for  
**IDEAS-TIH (Institute of Data Engineering, Analytics & Science Foundation)** under ISI Kolkata.

The chatbot is capable of answering user queries based strictly on information retrieved from  
IDEAS-TIH’s official website. It uses:

- **Scraped website data**  
- **FAISS similarity search**  
- **SentenceTransformer embeddings**  
- **Qwen2.5-1.5B-Instruct** (Open-source LLM)

The system is built entirely with **free and open-source tools** and runs fully offline.

This work was completed as a part of the **Autumn Internship 2025** under the mentorship of  
**Agnimitra Biswas**.

---

## 🚀 Features
- ✔ Fully open-source RAG implementation  
- ✔ Multi-URL website scraping (IDEAS-TIH pages)  
- ✔ Chunking + Embedding (MiniLM)  
- ✔ Vector search using FAISS  
- ✔ Local LLM inference using Qwen2.5  
- ✔ No API keys or paid services required  
- ✔ Terminal-based AI chatbot for Q&A  
- ✔ Modular design for easy extension  

---

## 🧱 Tech Stack  
| Component         | Technology Used                       |
|------------------|----------------------------------------|
| LLM              | Qwen2.5-1.5B-Instruct                  |
| Embeddings       | all-MiniLM-L6-v2 (SentenceTransformers) |
| Vector Database  | FAISS (IndexFlatL2)                    |
| Scraping         | BeautifulSoup4 + Requests              |
| Programming      | Python                                 |
| Environment      | Google Colab                           |

